# SAP CommerceSuite 1811.5

Aa per test, smarteditaddon is NOT required in manifest.json

	"storefrontAddons": [
		{
		    "addon": "smarteditaddon",
		    "storefront": "yacceleratorstorefront",
		    "template": "yacceleratorstorefront"
		}
	],
  
  This is consistent with the official wiki:
  
  AddOns
  
  https://help.sap.com/viewer/1be46286b36a4aa48205be5a96240672/SHIP/en-US/9a3ab7d08c704fccb7fd899e876d41d6.html
  
  If your code repository contains a storefront that is generated from a template with AddOns already installed, there is no need to configure it in the manifest.
  
