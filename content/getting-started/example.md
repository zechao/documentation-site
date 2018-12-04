+++
title = "Runnable example"
pagetitle = ""
description = ""
icon = "fa-question-circle" 
weight = 15
alwaysopen = true
+++

# This is an example of runnable shortcode

{{< runnable auth="Apikey 64780338-49c8-4439-7c7d-d03c2033b145" exampleGO="HOLA">}}
{
  hotelX {
    runtimeConfiguration(supplierCode:"prf911"){
      code
    }
  }
}
{{< /runnable >}}

{{% runnable-modal %}}