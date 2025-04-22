# Translized Redirect Website

A simple website that automatically redirects visitors from translized.com to app.translized.com.

## Functionality

- Automatically redirects visitors from translized.com or www.translized.com to app.translized.com
- Preserves any path or query parameters in the URL during redirection
- Shows a loading spinner during redirection
- Provides a manual redirect link if automatic redirection fails
- Has a clean, responsive design

## Deployment

To deploy this website:

1. Upload the `index.html` file to your web server
2. Add a logo image named `logo.png` to the same directory (optional)
3. Ensure the domain DNS is properly configured to point to your web server

## Local Testing

When testing locally, the site will redirect to app.translized.com after a 1.5-second delay.

## Notes

This is a minimal implementation focused solely on the redirection functionality. The script preserves any path or query parameters when redirecting to ensure a seamless experience. 