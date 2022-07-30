# https://zerodevx.github.io/zero-md/


# using <zero-md> web component.
## https://stackoverflow.com/questions/37770620/how-to-include-markdown-md-files-inside-html-files


<!-- Lightweight client-side loader that feature-detects and load polyfills only when necessary -->
<script src="https://cdn.jsdelivr.net/npm/@webcomponents/webcomponentsjs@2/webcomponents-loader.min.js"></script>

<!-- Load the element definition -->
<script type="module" src="https://cdn.jsdelivr.net/gh/zerodevx/zero-md@1/src/zero-md.min.js"></script>

<!-- Simply set the `src` attribute to your MD file and win -->
<zero-md src="README.md"></zero-md>