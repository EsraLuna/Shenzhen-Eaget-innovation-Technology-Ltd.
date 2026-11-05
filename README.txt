EAGET PORTFOLIO WEBSITE - HOW TO USE
====================================

FILES
  index.html      the website (design + search)
  certs.js        list of certificates: number -> PDF file (edit this to add more)
  logo.png        your logo
  certificates/   your PDF reports (file name = certificate number)

HOW THE SEARCH WORKS
  A visitor types a certificate number (e.g. CISCR251211120) and the PDF opens
  on the page with an EAGET watermark. Upper/lower case and spaces do not matter.
  Direct link / QR code:  https://YOUR-DOMAIN/?cert=CISCR251211120

ADD A NEW CERTIFICATE
  1. Copy the PDF into the "certificates" folder.
  2. Open certs.js, copy the CISCR251211120 block, change the number, details
     and pdf file name. Save and upload again.

PUT IT ONLINE (pick one - all can use your own domain name)
  A. Netlify (easiest, free): go to app.netlify.com/drop and drag the whole
     folder onto the page. You get a live link in seconds.
  B. Cloudflare Pages (free): Workers & Pages > Create > Pages > Upload assets.
  C. GitHub Pages (free): upload the files to a repository, then
     Settings > Pages > deploy from branch.
  D. Normal web hosting (cPanel/FTP): upload all files into public_html.

EDIT TEXT
  Open index.html in any text editor. Search for "Add your company story" and
  "Email and phone" to replace the placeholders with your real details.

NOTE
  The watermark covers the viewer on the web page only. People who click
  "Download PDF" receive the original file.
