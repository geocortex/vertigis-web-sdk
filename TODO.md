-   Fix portal.json 404
    -   Request is unnecessary in this case
-   Disable code splitting (if possible) and call it out in readme. Validate behavior of `import()`
-   Flesh out README.md in template with additional info and validate hyperlinks
-   Develop against an existing app use case - instead of using app/layout in template?
-   Use Case that needs investigation (may run into issues):
    -   Develop library, upload to app via designer and push to prod
    -   Go to make changes to same library and test in designer (this functionality doesn't yet exist)
    -   We are now loading duplicate libraries. What happens now? GAD could handle this by not loading the existing library resource, but we don't have a good way to match which existing library resource is the current dev library
