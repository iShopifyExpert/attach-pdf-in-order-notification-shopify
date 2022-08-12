# attach-pdf-in-order-notification-shopify
Attach PDF in Order Notification Shopify


        {%- if shop.refund_policy.body != blank -%}
          {{ shop.refund_policy | attach_as_pdf: "Handelsbetingelser" }}
        {%- endif -%}
