# Attach pdf in order notification Shopify
Attach PDF in Order Notification Shopify


        {%- if shop.refund_policy.body != blank -%}
          {{ shop.refund_policy | attach_as_pdf: "Handelsbetingelser" }}
        {%- endif -%}
