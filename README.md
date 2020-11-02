# Calculadora-Html-Css-Js
<!DOCTYPE html>
<html>
    <head>
            <meta charset="UTF-8">
            <meta name="viewport" content="width=device-width,
            initial-scale=1.0">
            <meta http-equiv="X-UA-Compatible" content="ie=edge">
            <title>Calculadora</title>
            <link href="Style.css" rel="stylesheet">
            <script src="Script.js" defer></script>

    </head>
    <body>
        <div class="grid">
            <div class="output">
                <div data-previous-op class="previous-Op"></div>
                <div data-current-op class="current-Op"></div>
            </div>
        
            <button data-all-clear class="span-two">AC</button>
            <button data-delete>DEL</button>
            <button data-op>%</button>
            <button data-num>1</button>
            <button data-num>2</button>
            <button data-num>3</button>
            <button data-op>*</button>
            <button data-num>4</button>
            <button data-num>5</button>
            <button data-num>6</button>
            <button data-op>+</button>
            <button data-num>7</button>
            <button data-num>8</button>
            <button data-num>9</button>
            <button data-num>-</button>
            <button data-num>.</button>
            <button data-num>0</button>
            <button data-equals class="span-two">=</button>
        </div>
        <div>
            <input type="checkbox" class="checkbox" id="chk" />
            <label class="label" for="chk">
                <i class="mode-night"></i>
                <i class="mode-light"></i>
                <div class="ball"></div>
            </label>
        </div>
    </body>

</html>
