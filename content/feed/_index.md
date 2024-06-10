<style>
        /* Container for the horizontal timeline */
        #twitter-timeline-container {
            overflow-x: auto; /* Enable horizontal scrolling */
            white-space: nowrap; /* Prevent line breaks */
        }

        /* Style the iframe container */
        .twitter-timeline {
            display: inline-block;
            vertical-align: top;
            white-space: normal; /* Allow wrapping within each tweet */
            width: 300px; /* Adjust width of each tweet */
            margin-right: 10px; /* Space between tweets */
        }
    </style>
<div class="twitter-timeline-container">
<a class="twitter-timeline" href="https://twitter.com/MICCAI_Society?ref_src=twsrc%5Etfw" style="display: none;">Tweets by MICCAI_Society</a>
</div>
 <script async src="https://platform.twitter.com/widgets.js" charset="utf-8"></script>
  <script>
        window.addEventListener('load', function() {
            const container = document.getElementById('twitter-timeline-container');

            // Wait until the iframe is loaded and modify its content
            const observer = new MutationObserver(() => {
                const iframe = container.querySelector('iframe');
                if (iframe) {
                    iframe.onload = () => {
                        const iframeDoc = iframe.contentDocument || iframe.contentWindow.document;
                        iframeDoc.documentElement.style.overflowX = 'auto'; // Enable horizontal scrolling within the iframe
                        iframeDoc.documentElement.style.whiteSpace = 'nowrap'; // Prevent line breaks inside the iframe
                    };
                }
            });

            observer.observe(container, { childList: true });
        });
    </script>