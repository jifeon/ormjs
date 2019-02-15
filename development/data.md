

{% api-method method="delete" host="https://plyo.io" path="/api/displayManager/:id/display/:adId" %}
{% api-method-summary %}
Delete ad
{% endapi-method-summary %}

{% api-method-description %}

{% endapi-method-description %}

{% api-method-spec %}
{% api-method-request %}
{% api-method-path-parameters %}
{% api-method-parameter name="Param" type="string" required=true %}

{% endapi-method-parameter %}

{% api-method-parameter name="param2" type="object" required=false %}
blah blah blah
{% endapi-method-parameter %}
{% endapi-method-path-parameters %}

{% api-method-query-parameters %}
{% api-method-parameter name=":id" type="string" required=true %}
UUID
{% endapi-method-parameter %}
{% endapi-method-query-parameters %}

{% api-method-body-parameters %}
{% api-method-parameter name="bodyInGet" type="string" required=false %}
Crazzy man
{% endapi-method-parameter %}
{% endapi-method-body-parameters %}
{% endapi-method-request %}

{% api-method-response %}
{% api-method-response-example httpCode=200 %}
{% api-method-response-example-description %}

{% endapi-method-response-example-description %}

{% code-tabs %}
{% code-tabs-item title="Filename" %}
```javascript
{
    "IT": "IS JSON"
}
```
{% endcode-tabs-item %}

{% code-tabs-item title=undefined %}
```
Plain text
```
{% endcode-tabs-item %}
{% endcode-tabs %}
{% endapi-method-response-example %}
{% endapi-method-response %}
{% endapi-method-spec %}
{% endapi-method %}

