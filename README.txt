Backplack Plugin Documentation, TL;DR Edition

(1) <script src="where/is/scratchblocks.js"></script>
(2) <script src="where/is/backpack.js"></script>
(3) <script>
        scratchblocks.renderMatching('pre.blocks', {
          languages: scratchblocks._currentLanguages,
          replace: function(el, svg, doc, options) {
            scratchblocks.replace(el, svg, doc, options);
    >>>>    el.appendChild(scratchblocks.backpackButton(el));
          },
        });
(4) Profit
