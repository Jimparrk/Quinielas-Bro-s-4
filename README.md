# Quinielas-Bro-s-4
Quinielas

<body>
    <p id="bolsa"><br><span id="bolsatxt"></span><span id="cantidad" style="color:yellow"></span></p>
    <div class="quiniela" id="quiniela" style="height: 375px;">
        <div class="aux"><h3 style="padding: 5px 7px" onclick="clean()"><ion-icon name="close-outline" role="img" class="md hydrated" aria-label="close outline"></ion-icon></h3></div>
        <div class="partido">
            <span id="L1" onclick="selection(this)"></span>
            <div id="_"></div>
            <span id="E1" onclick="selection(this)"></span>
            <div id="_"></div>
            <span id="V1" onclick="selection(this)"></span>
        </div>
        <div class="partido">
            <span id="L2" onclick="selection(this)"></span>
            <div id="_"></div>
            <span id="E2" onclick="selection(this)"></span>
            <div id="_"></div>
            <span id="V2" onclick="selection(this)"></span>
        </div>
        <div class="partido">
            <span id="L3" onclick="selection(this)"></span>
            <div id="_"></div>
            <span id="E3" onclick="selection(this)"></span>
            <div id="_"></div>
            <span id="V3" onclick="selection(this)"></span>
        </div>
        <div class="partido">
            <span id="L4" onclick="selection(this)"></span>
            <div id="_"></div>
            <span id="E4" onclick="selection(this)"></span>
            <div id="_"></div>
            <span id="V4" onclick="selection(this)"></span>
        </div>
        <div class="partido">
            <span id="L5" onclick="selection(this)"></span>
            <div id="_"></div>
            <span id="E5" onclick="selection(this)"></span>
            <div id="_"></div>
            <span id="V5" onclick="selection(this)"></span>
        </div>
        <div class="partido">
            <span id="L6" onclick="selection(this)"></span>
            <div id="_"></div>
            <span id="E6" onclick="selection(this)"></span>
            <div id="_"></div>
            <span id="V6" onclick="selection(this)"></span>
        </div>
        <div class="partido">
            <span id="L7" onclick="selection(this)"></span>
            <div id="_"></div>
            <span id="E7" onclick="selection(this)"></span>
            <div id="_"></div>
            <span id="V7" onclick="selection(this)"></span>
        </div>
        <div class="partido">
            <span id="L8" onclick="selection(this)"></span>
            <div id="_"></div>
            <span id="E8" onclick="selection(this)"></span>
            <div id="_"></div>
            <span id="V8" onclick="selection(this)"></span>
        </div>
        <div class="partido">
            <span id="L9" onclick="selection(this)"></span>
            <div id="_"></div>
            <span id="E9" onclick="selection(this)"></span>
            <div id="_"></div>
            <span id="V9" onclick="selection(this)"></span>
        </div>
    <div class="partido">
            <span id="L10" onclick="selection(this)"></span>
            <div id="_"></div>
            <span id="E10" onclick="selection(this)"></span>
            <div id="_"></div>
            <span id="V10" onclick="selection(this)"></span>
        </div>
        <h1 id="text">_&nbsp;&nbsp;_&nbsp;&nbsp;_&nbsp;&nbsp;_&nbsp;&nbsp;_&nbsp;&nbsp;_&nbsp;&nbsp;_&nbsp;&nbsp;_&nbsp;&nbsp;_&nbsp;&nbsp;_</h1>
    </div>
    <table class="botonera">
    <tbody><tr>
        <td width="37%">
            <h2 class="botonenviar" onclick="send()"> Enviar <span>1</span>&nbsp; <img src="./Quiniela Jalisco_files/whatsapp-logo-5.png" height="23px" style="position: absolute;"></h2>
        </td>
        <td width="14%">
            <h2 id="botonlisto" onclick="save()"><ion-icon name="add-outline" role="img" class="md hydrated" aria-label="add outline"></ion-icon></h2>
        </td>
        <td width="14%"> 
            <h2 id="botonborrar" onclick="deleteall()"><ion-icon name="trash-outline" id="trash" role="img" class="md hydrated" aria-label="trash outline"></ion-icon></h2>
        </td>
        <td width="35%">
            <table id="nombrebox">
                <tbody><tr style="height: 9px"><td id="nombretext"> &nbsp; Nombre</td><td></td></tr>
                <tr style="height: 20px"><td><input id="nombre" type="text" placeholder="" maxlength="20" spellcheck="false"></td><td><label id="borrarnombre" onclick="clearname()"><ion-icon name="backspace" role="img" class="md hydrated" aria-label="backspace"></ion-icon></label></td></tr>
            </tbody></table>
        </td>
    </tr>
    </tbody></table>
        <!--<input type="checkbox" id="checkcombinaciones" onclick="allowcombination()"><h6> <ion-icon name="apps"></ion-icon></h6>-->
        <table style="margin-top: 3px; width:100%">
            <tbody><tr>
                <td style="width: 37%">
                    <label id="random" onclick="random()">Aleatorio</label>
                </td>
                <td style="width: 40%">
                    <label id="checkcombinaciones" onclick="allowcombination()">
                        Dobles y Triples
                    </label>
                </td>
                <td style="width: 23%"></td>
            </tr>
        </tbody></table>
        <!--<script src="https://unpkg.com/ionicons@5.1.2/dist/ionicons.js"></script>-->

        <br><br>

    <div>
    <h4 id="costo">Costo: $0</h4><h4 id="total">Total: $25
</h4><br>
    </div>
    <div>
        <h4 id="numquinielas">0 Quiniela(s)</h4>
    </div>
    <br>
    <!--<p id="display"></p>-->
    <div id="divaux" translate="no">
        <table id="display">
        <tbody><tr><td style="width: 6.3%;">L</td><td style="width: 6.3%;">E</td><td style="width: 6.3%;">E</td><td style="width: 6.3%;">L</td><td style="width: 6.3%;">V</td><td style="width: 6.3%;">L</td><td style="width: 6.3%;">E</td><td style="width: 6.3%;">V</td><td style="width: 6.3%;">L</td><td style="width: 6.3%;">V</td><td class="cellname" style="font-size: small; overflow: hidden; border: none;"><pre>Jaime</pre></td><td id="x0" class="deleter" style="width: 6.3%; border: none;"><ion-icon name="close-circle" style="color:rgb(120,0,0);" role="img" class="md hydrated" aria-label="close circle"></ion-icon></td></tr></tbody></table>
    </div>
    <!--<button id="undo" onclick="remove()"><ion-icon name="arrow-undo-outline"></ion-icon></button>-->
    <br>

</body><app-content ng-version="11.1.0"></app-content></html>
