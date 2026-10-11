---
layout: default
title: "Shri Ajay Kumar Dey — My Life"
---

# My Life
## In the flow of ideas.

A digital portfolio and research-literary archive of **Ajay Kumar Dey (Pranabanandan)** — bringing together historical research, Bengali literature, devotional writing, books, poetry, and intellectual work.

---

### Featured Services & Bookings
* **Bhagwat Path Seva:** For Bhagwat Path, Katha, and devotional programmes, you can submit booking inquiries via your linked Google Form.

---

### The Archive: Three Worlds, One Intellectual Journey

1. **Research Desk**  
   Historical studies, source-based essays, academic notes, references, and long-form research articles.
2. **Katha & Seva**  
   Devotional literature, Bhagwat Katha material, spiritual reflections, and service-oriented writing.
3. **Literary Room**  
   Bengali poems, Vaishnava Padavali, books, lyrics, and other literary creations.

---

### Recent Articles & Publications

{% for post in site.posts limit:5 %}
* [{{ post.title }}]({{ post.url }}) — {{ post.date | date: "%B %d, %Y" }}
  {{ post.excerpt }}
{% endfor %}

---

> "Knowledge becomes an archive when research, memory and expression are brought together."
> — **Ajay Kumar Dey**
