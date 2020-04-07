# API

Foreflow exposes an API that can be used to obtain data from the foreflow instance.  In order to access the API, you will need to create an API key within your foreflow instance. API keys can be managed by clicking the "API Keys" link in the navigation menu.

## Creating API Keys

To create a new API key, click the "Add API Key" button on the API Keys page.  The system will ask for a description of the API Key.  This description field is best used to describe which system or application will be using the API Key.

Once an API Key is generated, foreflow will only display the key one time.  You should copy the key, and store it in a secure location.

API keys expire one year after they were created.

## Using an API Key

In order to use an API key, you will need to have a Dataset that has been enabled for API access.  When a dataset has been enabled for API access, a URL will appear in the index table for the dataset. 

To access the API for a given dataset, you will need to send a GET request to the URL that corresponds to the dataset.  You will include your API key as a parameter on the request, using ```ak``` as the name of the parameter.  Below is an example of an API request.

```
https://www.foreflow.com/foreflow/api/v1/datasets/ff4d6a54-06fd-4c8f-8918-77b4d1eee2e8?ak={api_key}
```


