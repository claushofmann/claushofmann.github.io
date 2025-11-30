---
# An instance of the Contact widget.
# Documentation: https://sourcethemes.com/academic/docs/page-builder/
widget: contact

# This file represents a page section.
headless: true

# Order that this section appears on the page.
weight: 130

title: Contact
subtitle: If you're interested in talking about all things ML, just drop me a line. 

content:
  # Automatically link email and phone or display as text?
  autolink: True
  
  # Email form provider
  form:
    provider: netlify
    formspree:
      id:
    netlify:
      # Enable CAPTCHA challenge to reduce spam?
      captcha: false
  
design:
  columns: '2'
---
Prefer email? Reach me at {{< email "hi" "claus-hofmann.com" "hi@claus-hofmann.com">}}. I'm also active on {{< staticref "https://x.com/ClausHofm" "newtab" >}}X{{< /staticref >}} and {{< staticref "https://www.linkedin.com/in/claus-hofmann/" "newtab" >}}LinkedIn{{< /staticref >}}.