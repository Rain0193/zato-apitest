
Given SOAP action "{value}"
=============================================================================================================

Usage example
-------------

```
Feature: zato-apitest docs

Scenario: Given SOAP action "{value}"

    Given address "http://apitest-demo.zato.io"
    Given URL path "/demo/xml"
    Given format "XML"
    Given SOAP action "my:soap:action"

    When the URL is invoked

    Then status is "200"
```

Discussion
----------

(None)