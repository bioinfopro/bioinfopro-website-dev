---
layout: page
title: Home
---

# Welcome to Our Developer Platform
Elevate your technical standards with our suite of enterprise tools. We build the future of software infrastructure.

## Powerful Code Snippets
Because we are using Jekyll, standard markdown triple backticks automatically generate beautiful, syntax-ready code blocks styled with our **Deep Blue** background.

```python
def authenticate_user(token):
    # Validates against our secure backend
    if is_valid(token):
        return True
    return False
```

## Reusable Banners (Using Includes)
Whenever you want to break up the text with a Call to Action, you can use our `banner.html` include:

{% include banner.html title="Interactive Assessments" text="Test candidates in real-world environments." button_text="View Demo" link="/about" %}

## Structured Layouts (PMI Inspired)
You can seamlessly drop pure HTML directly into your markdown if you want a specific card grid.

<div class="features-grid">
    <div class="feature-card">
        <h3>Security Auditing</h3>
        <p>Enterprise penetration testing tailored for your corporate infrastructure.</p>
        <a href="#">Learn More &rarr;</a>
    </div>
    <div class="feature-card">
        <h3>Agile Training</h3>
        <p>SCRUM certifications designed for modern product and engineering managers.</p>
        <a href="#">Learn More &rarr;</a>
    </div>
</div>

## Kramdown Attribute CSS
Don't want to write HTML? You can add CSS classes directly to standard markdown blocks like this:

This is a special highlighted callout block for important warnings or notes! It uses the gray and Pacific Blue colors automatically.
{: .callout }

This one uses the Royal Orchid accent color!
{: .callout .callout-accent }

[Schedule a Consultation](#){: .btn }
