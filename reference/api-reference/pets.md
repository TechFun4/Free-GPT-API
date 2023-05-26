# Pets

## Making a GPT Request

{% swagger baseUrl="https://ai.techfun.me" method="post" path="/gpt" summary="Get a response from GPT" %}
{% swagger-description %}

{% endswagger-description %}

{% swagger-parameter in="body" name="q" required="true" type="string" %}
Input for GPT
{% endswagger-parameter %}

{% swagger-response status="200" description="Pet successfully created" %}
```javascript
{
    "name"="Wilson",
    "owner": {
        "id": "sha7891bikojbkreuy",
        "name": "Samuel Passet",
    "species": "Dog",}
    "breed": "Golden Retriever",
}
```
{% endswagger-response %}

{% swagger-response status="400: Bad Request" description="Bad parameters" %}

{% endswagger-response %}

{% swagger-response status="500: Internal Server Error" description="An error occured" %}

{% endswagger-response %}
{% endswagger %}

{% hint style="info" %}
**Good to know:** This API method was created using the API Method block, it's how you can build out an API method documentation from scratch. Have a play with the block and you'll see you can do some nifty things like add and reorder parameters, document responses, and give your methods detailed descriptions.
{% endhint %}

## Updating a pet

{% swagger src="https://petstore.swagger.io/v2/swagger.json" path="/pet" method="put" %}
[https://petstore.swagger.io/v2/swagger.json](https://petstore.swagger.io/v2/swagger.json)
{% endswagger %}

{% hint style="info" %}
**Good to know:** This API method was auto-generated from an example Swagger file. You'll see that it's not editable – that's because the contents are synced to a URL! Any time the linked file changes, the documentation will change too.
{% endhint %}
