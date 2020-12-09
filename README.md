<html>
<head>
<script>
var guess = 3;
var win = 0;
var bonus = 2
var ne1 = 1;
var ne2 = 1;
var ne3 = 1;
                    var ne4 = 1;
                    var ne5 = 1;
                    var ne6 = 1;
                    var ne7 = 1;
                    var ne8 = 1;
                    var ne9 = 1;
                    var taip1 = 1;
var taip2 = 1;
var taip3 = 1;
function neteisingas1() {
                        if (guess > 0 && win != 2 && ne1 == 1) { //Taškų nuėmimas (šiuo atvėju -1 paspaudus)
                            ne1 -= 1 //Paspaudus minusuojamas spėjimas
                            document.getElementById("atsakymas")
                                .innerHTML = "Neteisingas, spėk dar kartą! ❌"; //Išvestis apačioje dėl spėjimo
                            guess -= 1 //Atimimas iš dabartinio spėjimų skaičiaus
                            document.getElementById("sprendimai") //Dabartinis bandymų skaičius
                                .innerHTML = guess; //Spėjimų skaičius
                            document.getElementById("npirmas") //ID priskirtas button'ui
                                .innerHTML = "Neteisingas"; //Atsakymas ar teisinga kortelė ar ne
  } else { //jei neleika bandymų, tada print (nebeliko...)
                            document.getElementById("atsakymas")
                                .innerHTML = "Nebeliko bandymų, jau spaudei šią kortelę arba laimėjai žaidimą! 😕"; //Atsakymas jei nebelieka bandymų
                            document.getElementById("sprendimai") //Dabartinis bandymų skaičius
                                .innerHTML = guess; //Spėjimų skaičius
                        }
                    }

function neteisingas2() { //kartojasi "neigiamos" funkcijos seka
                        if (guess > 0 && win != 2 && ne2 == 1) {
                            ne2 -= 1
                            document.getElementById("atsakymas")
                                .innerHTML = "Neteisingas, spėk dar kartą! ❌";
                            guess -= 1
                            document.getElementById("sprendimai")
                                .innerHTML = guess;
                            document.getElementById("nantras")
                                .innerHTML = "Neteisingas";

 } else {
                            document.getElementById("atsakymas")
                                .innerHTML = "Nebeliko bandymų, jau spaudei šią kortelę arba laimėjai žaidimą! 😕";
                            document.getElementById("sprendimai")
                                .innerHTML = guess;
                        }
                    }

function neteisingas3() { //kartojasi "neigiamos" funkcijos seka
                        if (guess > 0 && win != 2 && ne3 == 1) {
                            ne3 -= 1
                            document.getElementById("atsakymas")
                                .innerHTML = "Neteisingas, spėk dar kartą! ❌";
                            guess -= 1
                            document.getElementById("sprendimai")
                                .innerHTML = guess;
                            document.getElementById("ntrecias")
                                .innerHTML = "Neteisingas";

} else {
                            document.getElementById("atsakymas")
                                .innerHTML = "Nebeliko bandymų, jau spaudei šią kortelę arba laimėjai žaidimą! 😕";
                            document.getElementById("sprendimai")
                                .innerHTML = guess;
                        }
                    }

function neteisingas4() { //kartojasi "neigiamos" funkcijos seka
                        if (guess > 0 && win != 2 && ne4 == 1) {
                            ne4 -= 1
                            document.getElementById("atsakymas")
                                .innerHTML = "Neteisingas, spėk dar kartą! ❌";
                            guess -= 1
                            document.getElementById("sprendimai")
                                .innerHTML = guess;
                            document.getElementById("nketvirtas")
                                .innerHTML = "Neteisingas";

 } else {
                            document.getElementById("atsakymas")
                                .innerHTML = "Nebeliko bandymų, jau spaudei šią kortelę arba laimėjai žaidimą! 😕";
                            document.getElementById("sprendimai")
                                .innerHTML = guess;
                        }
                    }

 function neteisingas5() { //kartojasi "neigiamos" funkcijos seka
                        if (guess > 0 && win != 2 && ne5 == 1) {
                            ne5 -= 1
                            document.getElementById("atsakymas")
                                .innerHTML = "Neteisingas, spėk dar kartą! ❌";
                            guess -= 1
                            document.getElementById("sprendimai")
                                .innerHTML = guess;
                            document.getElementById("npenktas")
                                .innerHTML = "Neteisingas";

} else {
                            document.getElementById("atsakymas")
                                .innerHTML = "Nebeliko bandymų, jau spaudei šią kortelę arba laimėjai žaidimą! 😕";
                            document.getElementById("sprendimai")
                                .innerHTML = guess;
                        }
                    }

function neteisingas6() { //kartojasi "neigiamos" funkcijos seka
                        if (guess > 0 && win != 2 && ne6 == 1) {
                            ne6 -= 1
                            document.getElementById("atsakymas")
                                .innerHTML = "Neteisingas, spėk dar kartą! ❌";
                            guess -= 1
                            document.getElementById("sprendimai")
                                .innerHTML = guess;
                            document.getElementById("nsestas")
                                .innerHTML = "Neteisingas";

 } else {
                            document.getElementById("atsakymas")
                                .innerHTML = "Nebeliko bandymų, jau spaudei šią kortelę arba laimėjai žaidimą! 😕";
                            document.getElementById("sprendimai")
                                .innerHTML = guess;
                        }
                    }

 function neteisingas7() { //kartojasi "neigiamos" funkcijos seka
                        if (guess > 0 && win != 2 && ne7 == 1) {
                            ne7 -= 1
                            document.getElementById("atsakymas")
                                .innerHTML = "Neteisingas, spėk dar kartą! ❌";
                            guess -= 1
                            document.getElementById("sprendimai")
                                .innerHTML = guess;
                            document.getElementById("nseptintas")
                                .innerHTML = "Neteisingas";

 } else {
                            document.getElementById("atsakymas")
                                .innerHTML = "Nebeliko bandymų, jau spaudei šią kortelę arba laimėjai žaidimą! 😕";
                            document.getElementById("sprendimai")
                                .innerHTML = guess;
                        }
                    }

 function neteisingas8() { //kartojasi "neigiamos" funkcijos seka
                        if (guess > 0 && win != 2 && ne8 == 1) {
                            ne8 -= 1
                            document.getElementById("atsakymas")
                                .innerHTML = "Neteisingas, spėk dar kartą! ❌";
                            guess -= 1
                            document.getElementById("sprendimai")
                                .innerHTML = guess;
                            document.getElementById("nastuntas")
                                .innerHTML = "Neteisingas";

 } else {
                            document.getElementById("atsakymas")
                                .innerHTML = "Nebeliko bandymų, jau spaudei šią kortelę arba laimėjai žaidimą! 😕";
                            document.getElementById("sprendimai")
                                .innerHTML = guess;
                        }
                    }

 function neteisingas9() { //kartojasi "neigiamos" funkcijos seka
                        if (guess > 0 && win != 2 && ne9 == 1) {
                            ne9 -= 1
                            document.getElementById("atsakymas")
                                .innerHTML = "Neteisingas, spėk dar kartą! ❌";
                            guess -= 1
                            document.getElementById("sprendimai")
                                .innerHTML = guess;
                            document.getElementById("ndevintas")
                                .innerHTML = "Neteisingas";

  } else {
                            document.getElementById("atsakymas")
                                .innerHTML = "Nebeliko bandymų, jau spaudei šią kortelę arba laimėjai žaidimą! 😕";
                            document.getElementById("sprendimai")
                                .innerHTML = guess;
                        }
                    }

 function teisingas1() { //tokia pati funkcija kaip "neigiamos"
                        if (guess > 0 && win != 2 && taip1 == 1) {
                            document.getElementById("atsakymas")
                                .innerHTML = "Teisingai! Rask kitą atsakymą, dabar gauni 1 papildomą spėjimą!";
                            guess += 1 //prisideda spėjimas
                            win += 1 //prisideda atsakymas
                            document.getElementById("sprendimai")
                                .innerHTML = guess;
                            document.getElementById("tpirmas")
                                .innerHTML = "Teisingas";
                            if (win >= 2) { //jei daugiau nei du atsakymus turi, laimi
                                document.getElementById("atsakymas") //pagal id įrašo atsakymą
                                    .innerHTML = "Laimėjai žaidimą, sveikinu! 🎂"; //jei laimi žaidimą išmeta šį atsakymą

                            }
  } else {
                            document.getElementById("atsakymas")
                                .innerHTML = "Nebeliko bandymų, jau spaudei šią kortelę arba laimėjai žaidimą! 😕";
                            document.getElementById("sprendimai")
                                .innerHTML = guess;
                        }
                        if (win >= 2) {
                            document.getElementById("atsakymas")
                                .innerHTML = "Laimėjai žaidimą, sveikinu! 🎂";
                                }
                    }

 function teisingas2() { //kartojasi teisingoji funkcija
                        if (guess > 0 && win != 2 && taip2 == 1) {
                            document.getElementById("atsakymas")
                                .innerHTML = "Teisingai! Rask kitą atsakymą, dabar gauni 1 papildomą spėjimą!";
                            guess += 1
                            win += 1
                            document.getElementById("sprendimai")
                                .innerHTML = guess;
                            document.getElementById("ttrecias")
                                .innerHTML = "Teisingas";
                            if (win >= 2) {
                                document.getElementById("atsakymas")
                                    .innerHTML = "Laimėjai žaidimą, sveikinu! 🎂";

                            }
  } else {
                            document.getElementById("atsakymas")
                                .innerHTML = "Nebeliko bandymų, jau spaudei šią kortelę arba laimėjai žaidimą! 😕";
                            document.getElementById("sprendimai")
                                .innerHTML = guess;
                        }
                        if (win >= 2) {
                            document.getElementById("atsakymas")
                                .innerHTML = "Laimėjai žaidimą, sveikinu! 🎂";
  }
  }

 function teisingas3() { //kartojasi teisingoji funkcija
                        if (guess > 0 && win != 2 && taip3 == 1) {
                            document.getElementById("atsakymas")
                                .innerHTML = "Teisingai! Rask kitą atsakymą, dabar gauni 1 papildomą spėjimą!";
                            guess += 1
                            win += 1
                            document.getElementById("sprendimai")
                                .innerHTML = guess;
                            document.getElementById("tantras")
                                .innerHTML = "Teisingas";
                            if (win >= 2) {
                                document.getElementById("atsakymas")
                                    .innerHTML = "Laimėjai žaidimą, sveikinu! 🎂";

                            }
  } else {
                            document.getElementById("atsakymas")
                                .innerHTML = "Nebeliko bandymų, jau spaudei šią kortelę arba laimėjai žaidimą! 😕";
                            document.getElementById("sprendimai")
                                .innerHTML = guess;
                        }
                        if (win >= 2) {
                            document.getElementById("atsakymas")
                                .innerHTML = "Laimėjai žaidimą, sveikinu! 🎂";

  }
                    }
                </script>

          

 <h1>Žaidimas</h1>

<p>Galimi 3 bandymui, jei nerasti teisingų atsakymų pralaimėsi</p>

 <p>Likę bandymai:</p>
 <p id="sprendimai">3</p>

 <div>
<button class="button1" type="button" onclick="neteisingas1()" id="npirmas">Galimai tiks</button>
<button class="button2" type="button" onclick="neteisingas2()" id="nantras">Ne teisingas</button>
<button class="button1" type="button" onclick="teisingas1()" id="tpirmas">Klaidingas</button>
<button class="button2" type="button" onclick="neteisingas9()" id="ndevintas">Gal šitas?</button>
<br>
<button class="button3" type="button" onclick="neteisingas3()" id="ntrecias">Čia!</button>
<button class="button1" type="button" onclick="neteisingas4()" id="nketvirtas">Spėk</button>
<button class="button3" type="button" onclick="neteisingas5()" id="npenktas">Raudonas</button>
<button class="button1" type="button" onclick="teisingas3()" id="tantras">Nepasiduok</button>
<br>
<button class="button1" type="button" onclick="neteisingas6()" id="nsestas">Taškas</button>
<button class="button4" type="button" onclick="teisingas2()" id="ttrecias">Dešimtukas</button>
<button class="button1" type="button" onclick="neteisingas7()" id="nseptintas">Pergalė!</button>
<button class="button1" type="button" onclick="neteisingas8()" id="nastuntas">Pabandyk šį!</button>
</div>
<br>
<p id="atsakymas">Pabandyk laimę!</p>
</div>
</div>
</div>
</footer>
</body></html>
