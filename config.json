{
    "workflowApiVersion": "1.1",
    "metaData": {
        "icon": "images/icon.png",
        "iconSmall": "images/iconSmall.png",
        "category": "message"
    },
    "type": "REST",
    "lang": {
        "fr-FR": {
            "name": "Raccourcir l'URL",
          "description": "Raccourcir l'URL",
          "step1Label": "Entrer l'URL"
        }
    },
    "arguments": {
        "execute": {
           "inArguments":[],
          "outArguments": [],
          "url": "https://testsalesforceurl.herokuapp.com/journeybuilder/execute",
           "verb": "POST",
            "body": "",
            "header": "",
            "format": "json",
            "useJwt": true,
            "timeout": 10000
        }
    },
    "configurationArguments": {
      "applicationExtensionKey": "748e0c7c-be20-479f-aded-cec684714aad",
      "save": {
        "url": "https://testsalesforceurl.herokuapp.com/journeybuilder/save",
          "verb": "POST",
        "useJwt": true
       },
       "publish": {
        "url": "https://testsalesforceurl.herokuapp.com/journeybuilder/publish",
           "verb": "POST",
        "useJwt": true
       },
      "stop": {
        "url": "https://testsalesforceurl.herokuapp.com/journeybuilder/stop",
           "verb": "POST",
        "useJwt": true
      },
      "validate": {
        "url": "https://testsalesforceurl.herokuapp.com/journeybuilder/validate",
        "verb": "POST",
        "useJwt": true
      }
    },
    "wizardSteps": [
        { "label": "Entrer l'URL", "key": "step1" }
    ],
    "userInterfaces": {
        "configModal": {
            "height": 400,
            "width": 1000,
          "fullscreen": false
        }
    },
    "schema": {
        "arguments": {
            "execute": {
                "inArguments": [],
                "outArguments": []
            }
        }
    }
}
