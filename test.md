---
layout: page
title: Resources
permalink: /resources
---

# Test


    <div id="TEI">
      Sadly, this page will not work in Internet Explorer and some older browsers. We suggest you use a newer version of Chrome or Firefox.
    </div>
    <script src="../dist/CETEI.js"></script>
    <script>
      var CETEIcean = new CETEI();
      CETEIcean.getHTML5('BeggarsOpera.xml', function(data) {
        document.getElementById("TEI").innerHTML = "";
        document.getElementById("TEI").appendChild(data);
      });

      // Alternatively, use then()
      // (new CETEI).getHTML5('testTEI.xml').then(function(data){
      //   document.getElementById("TEI").appendChild(data);
      // });

    </script>
