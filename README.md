# basic-cell-mobile
<!DOCTYPE html>
<html>
    <body>
        <div id="nokia">
            <div id="screen">
                <div id="container">
                    <section id="screen-pin">
                        <div class="main">Enter PIN code:</div>
                        <input id="enterpin" type="password" readonly>
                        <div class="text-center">OK</div>
                    </section>
                    <section id="screen-standby">
                        <div class="text-right text-small" id="clock">&nbsp;</div>
                        <div class="main mb-m20">
                            <div class="levelbar" id="signal"></div>
                            <div class="text-center" id="signal-txt">--</div>
                            <div class="levelbar" id="battery"></div>
                        </div>
                        <div class="text-center">Menu</div>
                    </section>
                    <section id="screen-call">
                        <div class="main" id="call"></div>
                        <div class="text-center">Call</div>
                    </section>
                    <section id="screen-menu">
                        <div class="header">Menu</div>
                        <div class="main" id="menu"></div>
                        <div class="text-center">Select</div>
                        <div class="scrollbar"><span class="handle"></span></div>
                    </section>
                </div>
            </div>
            <div id="keypad">
                <div class="key" id="key-pow"></div>
                <div class="key" id="key-nav"></div>
                <div class="key" id="key-up"></div>
                <div class="key" id="key-clr"></div>
                <div class="key" id="key-down"></div>
            </div>
            <div id="numpad">
                <div class="key num" id="num-1"></div>
                <div class="key num" id="num-2"></div>
                <div class="key num" id="num-3"></div>
                <div class="key num" id="num-4"></div>
                <div class="key num" id="num-5"></div>
                <div class="key num" id="num-6"></div>
                <div class="key num" id="num-7"></div>
                <div class="key num" id="num-8"></div>
                <div class="key num" id="num-9"></div>
                <div class="key num" id="num-aste"></div>
                <div class="key num" id="num-0"></div>
                <div class="key num" id="num-hash"></div>
            </div>
        </div>
        <div style="display: none"><!-- cache images -->
            <img src="https://vignette.wikia.nocookie.net/khangnd/images/3/3d/Nokia-messages.png">
            <img src="https://vignette.wikia.nocookie.net/khangnd/images/8/8c/Nokia-contacts.png">
            <img src="https://vignette.wikia.nocookie.net/khangnd/images/6/67/Nokia-settings.png">
            <img src="https://vignette.wikia.nocookie.net/khangnd/images/1/1b/Nokia-tones.png">
            <img src="https://vignette.wikia.nocookie.net/khangnd/images/4/45/Nokia-extras.png">
        </div>
    </body>
</html>
