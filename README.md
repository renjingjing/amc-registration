# AMC Registration GitHub Pages Site

This is a static GitHub Pages version of the AMC registration page.

## How it works

- Host `index.html` on GitHub Pages.
- The form submits to `https://formsubmit.co/jenny@vsacamp.com`.
- Parent submissions and payment screenshots are emailed to `jenny@vsacamp.com`.
- The first submission requires email activation from FormSubmit.

## Important

GitHub Pages is static hosting. It cannot privately store submissions or run an admin dashboard by itself.
This version uses FormSubmit as the form backend.

FormSubmit file upload notes:

- The form uses `enctype="multipart/form-data"`.
- The payment screenshot field is named `attachment`.
- All uploaded files together must be 10 MB or less.

