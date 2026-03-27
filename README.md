# Emergency Locks Website

This repository contains the source code for the Emergency Locks locksmith service website.  The site is a single page built using HTML, Tailwind CSS and Font Awesome icons.  It provides an overview of services offered, pricing, contact details, an order form, and customer testimonials—all in Hebrew.

## Deployment

To host this site using GitHub Pages:

1. Create a new repository in your GitHub account (for example, `emergency-locks`).
2. Add the contents of this folder (`index.html`, `CNAME`, and this `README.md`) to the repository.
3. Commit and push the files to the `main` branch.
4. In the repository settings, enable GitHub Pages and select the root of the `main` branch as the source.
5. GitHub Pages will automatically deploy the `index.html` file.  The `CNAME` file configures the site to use the custom domain `emergency-locks.com`.  You will also need to update your domain's DNS settings to point to GitHub Pages (see below).

## DNS Configuration

To complete the connection of your custom domain to GitHub Pages, configure the DNS records where you registered the domain:

* For an **A** record, point `@` (or your root domain) to GitHub's Pages IP addresses: `185.199.108.153`, `185.199.109.153`, `185.199.110.153` and `185.199.111.153`.
* For an **AAAA** record (if your DNS provider supports IPv6), point `@` to: `2606:50c0:8000::153`, `2606:50c0:8001::153`, `2606:50c0:8002::153` and `2606:50c0:8003::153`.

After saving these DNS records, it may take some time for them to propagate.  Once they do, visiting `https://emergency-locks.com` should show your GitHub Pages site.

## License

This website was provided to you for personal use, and no license is implied.
