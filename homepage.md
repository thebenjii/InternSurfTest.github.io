---
layout: default
title: Internship Job App
permalink: /
---
# Welcome to InternSurf!

![App Logo](assets/logo.png)

Start your career journey with the best internship opportunities.

## Why Choose Us?

- **Extensive Listings**: Thousands of internships across various industries.
- **Easy Application**: Apply directly through our platform.
- **Personalized Matches**: Get internships that fit your profile.

## How It Works

1. **Create an Account**: Sign up with your email or social media.
2. **Complete Your Profile**: Tell us about your education and interests.
3. **Apply to Internships**: Browse and apply to internships that excite you.

## Get Started Today!

[Sign Up Now](signup.html)

---

---
layout: default
title: Internship Job App
permalink: /
---

# Welcome to InternHub!

![App Logo](assets/logo.png)

Start your career journey with the best internship opportunities.

## Latest Internship Openings

<div class="internship-list">
  {% for internship in site.internships %}
  <div class="internship-box">
    <h2>{{ internship.title }}</h2>
    <p><strong>Company:</strong> {{ internship.company }}</p>
    <p><strong>Location:</strong> {{ internship.location }}</p>
    <p><strong>Duration:</strong> {{ internship.duration }}</p>
    <p>{{ internship.description }}</p>
    <a href="{{ internship.apply_link }}">Apply Now</a>
  </div>
  {% endfor %}
</div>

## Why Choose Us?

<!-- Rest of your content -->


*© 2024 InternSurf. All rights reserved.*
