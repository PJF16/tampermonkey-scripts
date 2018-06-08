// ==UserScript==
// @name         Android-Hilfe.de-CustomHomepage
// @namespace    https://www.android-hilfe.de/
// @version      0.1
// @description  make android-hilfe.de more beautiful! Removes different unnecessary boxes on the landing page of Android-Hilfe.de
// @author       Philipp Johann Fritz (PJF16)
// @match        https://www.android-hilfe.de/
// @grant        none
// ==/UserScript==
//@require http://ajax.googleapis.com/ajax/libs/jquery/1.9.1/jquery.min.js
(function() {
    'use strict';

        $(document).ready(function() {
            //remove sidebar if screen width is smaller than 1300px
            if ($(window).width() < 1300) {
                $('.sidebar').remove();
                $('.mainContent').css("margin-right","0px");
            }
            //remove news box
            $('html>body>div:eq(0)>div:eq(1)>div>div>div:eq(1)>div:eq(0)>div>div>ol>li:eq(1)').remove();
            //remove popular devices box
            $('html>body>div:eq(0)>div:eq(1)>div>div>div:eq(1)>div:eq(0)>div>div>ol>li:eq(2)').remove();
        });
})();
