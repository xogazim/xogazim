- 👋 Hi, I’m @xogazim
- 👀 I’m interested in ...
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...

<!---
xogazim/xogazim is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
---{
	"openapi": "3.0.0",
	"info": {
		"title": "Google OAuth2",
		"description": "Obtains end-user authorization grants for use with other Google APIs.",
		"termsOfService": "",
		"version": "v2",
		"contact": {
			"name": "No Contact",
			"url": "http:\/\/example.com",
			"email": "adc80c@gmail.com"
		},
		"license": {
			"name": "No License",
			"url": "http:\/\/example.com"
		}
	},
	"servers": [{
		"url": "www.googleapis.com\/"
	}],
	"paths": {
		"\/oauth2\/v2\/certs": {
			"get": {
				"summary": "Get Certificate",
				"description": "Get the certification for this session.",
				"operationId": "oauth2.getCertForOpenIdConnect",
				"parameters": []
			}
		},
		"\/oauth2\/v2\/tokeninfo": {
			"post": {
				"summary": "Get Token Info",
				"description": "Get the token information for this session.",
				"operationId": "oauth2.tokeninfo",
				"parameters": [{
					"name": "access_token",
					"in": "query",
					"description": "",
					"schema": {
						"type": ""
					}
				},
				{
					"name": "id_token",
					"in": "query",
					"description": "",
					"schema": {
						"type": ""
					}
				},
				{
					"name": "token_handle",
					"in": "query",
					"description": "",
					"schema": {
						"type": "parameters"
					}
				}]
			}
		},
		"\/oauth2\/v2\/userinfo": {
			"get": {
				"summary": "Get User Info",
				"description": "Get the user information for this session.",
				"operationId": "oauth2.userinfo.get",
				"parameters": []
			}
		},
		"\/userinfo\/v2\/me": {
			"get": {
				"summary": "Get Me",
				"description": "Get the currently authenticated user for this session.",
				"operationId": "oauth2.userinfo.v2.me.get",
				"parameters": []
			}
		}
	},
	"components": {
		"schemas": {
			"Jwk": {
				"type": "object",
				"description": null,
				"properties": {
					"Jwk": {
						"type": "object",
						"description": null,
						"format": null
					}
				}
			},
			"keys": {
				"type": "parameters",
				"description": ""
			},
			"Tokeninfo": {
				"type": "object",
				"description": null,
				"properties": {
					"Tokeninfo": {
						"type": "object",
						"description": null,
						"format": null
					}
				}
			},
			"access_type": {
				"type": "parameters",
				"description": ""
			},
			"audience": {
				"type": "parameters",
				"description": ""
			},
			"email": {
				"type": "parameters",
				"description": ""
			},
			"expires_in": {
				"type": "parameters",
				"description": ""
			},
			"issued_to": {
				"type": "parameters",
				"description": ""
			},
			"scope": {
				"type": "parameters",
				"description": ""
			},
			"token_handle": {
				"type": "parameters",
				"description": ""
			},
			"user_id": {
				"type": "parameters",
				"description": ""
			},
			"verified_email": {
				"type": "parameters",
				"description": ""
			},
			"Userinfoplus": {
				"type": "object",
				"description": null,
				"properties": {
					"Userinfoplus": {
						"type": "object",
						"description": null,
						"format": null
					}
				}
			},
			"family_name": {
				"type": "parameters",
				"description": ""
			},
			"gender": {
				"type": "parameters",
				"description": ""
			},
			"given_name": {
				"type": "parameters",
				"description": ""
			},
			"hd": {
				"type": "parameters",
				"description": ""
			},
			"id": {
				"type": "parameters",
				"description": ""
			},
			"link": {
				"type": "parameters",
				"description": ""
			},
			"locale": {
				"type": "parameters",
				"description": ""
			},
			"name": {
				"type": "parameters",
				"description": ""
			},
			"picture": {
				"type": "parameters",
				"description": ""
			},
			"access_token": {
				"type": "",
				"description": ""
			},
			"id_token": {
				"type": "",
				"description": ""
			}
		}
	}
}
