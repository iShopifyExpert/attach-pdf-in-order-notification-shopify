# Attach pdf in order notification Shopify
Attach PDF in Order Notification Shopify


        Refund policy
        
        {%- if shop.refund_policy.body != blank -%}
          {{ shop.refund_policy | attach_as_pdf: "Refund-policy" }}
        {%- endif -%}
        
        Privacy policy
        
        {%- if shop.privacy_policy.body != blank -%}
          {{ shop.privacy_policy | attach_as_pdf: "Privacy-policy" }}
        {%- endif -%}
        
        Terms of service
        
        {%- if shop.terms_of_service.body != blank -%}
          {{ shop.terms_of_service | attach_as_pdf: "Terms-of-service" }}
        {%- endif -%}
        
        Shipping policy
        
        {%- if shop.shipping_policy.body != blank -%}
          {{ shop.shipping_policy | attach_as_pdf: "Shipping-policy" }}
        {%- endif -%}
        
        Contact information
        
        {%- if shop.contact_information.body != blank -%}
          {{ shop.contact_information | attach_as_pdf: "Contact information" }}
        {%- endif -%}
        
        Legal notice
        
        {%- if shop.legal_notice.body != blank -%}
          {{ shop.legal_notice | attach_as_pdf: "Legal notice" }}
        {%- endif -%}
        
