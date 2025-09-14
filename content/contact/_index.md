---
title: Contact Me
type: landing

design:
  background:
    image:
      filename: contact.jpg  # Place this image in `static/media/`
      size: cover
      position: center
      parallax: false
    color: "#ffffff"

sections:
  - block: markdown
    content:
      title: Office Hours
      text: |
        **Available Times:**
        - **Monday–Friday**: 9:00 – 12:45  
        - **Public holidays**: On request

        _All times are in Central European Time (CET)._

        <form action="https://formspree.io/f/xrbajkzw" method="POST" style="max-width:720px;margin:2rem auto 0;display:grid;grid-template-columns:1fr 1fr;gap:1rem;">
          <div>
            <label for="name">Name</label><br>
            <input id="name" name="name" type="text" required
                   style="width:100%;padding:.75rem;border:1px solid #ddd;border-radius:.5rem;">
          </div>

          <div>
            <label for="email">Email</label><br>
            <input id="email" name="email" type="email" required
                   style="width:100%;padding:.75rem;border:1px solid #ddd;border-radius:.5rem;">
          </div>

          <div style="grid-column:1/-1;">
            <label for="subject">Subject</label><br>
            <input id="subject" name="subject" type="text"
                   style="width:100%;padding:.75rem;border:1px solid #ddd;border-radius:.5rem;">
          </div>

          <div style="grid-column:1/-1;">
            <label for="message">Message</label><br>
            <textarea id="message" name="message" rows="6" required
                      style="width:100%;padding:.75rem;border:1px solid #ddd;border-radius:.5rem;"></textarea>
          </div>

          <!-- Honeypot -->
          <input type="text" name="_gotcha" style="display:none">

          <input type="hidden" name="_subject" value="New message from your website">

          <div style="grid-column:1/-1;display:flex;align-items:center;gap:.5rem;">
            <input id="consent" type="checkbox" required>
            <label for="consent" style="font-size:.95rem;">I consent to my data being used to contact me about this inquiry.</label>
          </div>

          <div style="grid-column:1/-1;">
            <button type="submit"
                    style="padding:.85rem 1.25rem;border:none;border-radius:.5rem;cursor:pointer;background:#007bff;color:white;">
              Send Message
            </button>
          </div>
        </form>
    design:
      background:
        color: "rgba(245, 245, 245, 0.6)"
      spacing:
        padding: ["4rem", "2rem", "4rem", "2rem"]

  - block: markdown
    content:
      title: Book an appointment
      text: |
        <div style="max-width: 900px; margin: auto; padding: 2rem;">
          <iframe
            src="https://calendly.com/mohandas8488"
            style="border: 0; width: 100%; height: 300px; border-radius: 12px;"
            frameborder="0"
            scrolling="no">
          </iframe>
        </div>
    design:
      background:
        color: "rgba(245, 245, 245, 0.6)"
      spacing:
        padding: ["4rem", "2rem", "4rem", "2rem"]
---
