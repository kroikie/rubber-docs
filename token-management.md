{% extends "_internal/templates/concept.html" %}
{% block title %}Managing {{messaging}} tokens{% endblock title %}
{% block body %}

{{firebase_messaging}} uses tokens to target messages. When a client
registers with {{firebase_messaging}} it gets a token that identifies
it. Developers can map these tokens for different types of app level
entities.

One common pattern is to map tokens to users. The following describes
a solution for managing tokens mapped to Firebase Auth users.

{% block body %}
