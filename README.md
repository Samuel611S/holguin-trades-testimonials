# Holguin Trades Testimonials Form

This repository contains the testimonials request form for Holguin Trades. The form is available in two versions:

1. `testimonial_request_ht_full_with_logo_2025_05_19.html` - Full version with logo
2. `testimonial_request_ht_to_embed_2025_05_19.html` - Embeddable version without logo

## Features

- Modern, responsive design
- Cloudflare Turnstile integration for spam prevention
- File upload support for photos and media
- Form validation
- Honeypot field for additional spam protection
- Industry and country dropdowns
- Rating system
- Service selection
- Consent management
- Test mode configuration

## Setup

1. Clone the repository
2. Update the Cloudflare Turnstile site key if needed
3. Configure the form action URL to point to your backend endpoint
4. Update the test email address if needed

## Usage

### Full Version
Use the full version (`testimonial_request_ht_full_with_logo_2025_05_19.html`) for standalone pages.

### Embeddable Version
Use the embeddable version (`testimonial_request_ht_to_embed_2025_05_19.html`) within an iframe on your website:

```html
<iframe src="path/to/testimonial_request_ht_to_embed_2025_05_19.html" 
        width="100%" 
        height="1000" 
        frameborder="0">
</iframe>
```

## Testing

The form is currently configured to send test submissions to `samuels.sameh@gmail.com`. To change this:

1. Update the `test_email` hidden field value
2. Update the form action URL to point to your test endpoint

## Security

- Cloudflare Turnstile integration
- Honeypot field
- File type validation
- Form validation
- Secure form submission

## Dependencies

- Cloudflare Turnstile API
- Modern browser with JavaScript enabled 