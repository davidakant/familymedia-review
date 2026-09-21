# FamilyMedia — review build

The built page only. The source is private, and there is no data here.

The page scans a folder the viewer chooses, in their own browser, and holds
what it finds in memory until the tab closes. Its Content Security Policy is
`connect-src 'none'`, so the browser refuses any network connection it tries
to make. Nothing is uploaded, and nothing can be.

Live: https://fm-review-2b9a81.netlify.app
