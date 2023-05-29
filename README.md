# redirect_firebase_cloud_function_url_to_another_url
How to redirect a cloud function url or other url to a custom url 





"hosting": {
  "rewrites": [
    {
      "source": "/custom-url",
      "function": "helloWorld"
    }
  ]
}


Then deploy : firebase deploy --only hosting
