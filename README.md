<!doctype html>

<head>
    <title>Fantastic Four</title>
    <style>
        body {
            background-color: lightblue;
        }
        .scroll-container {
            display: flex;
            width: 100%;             /* Pas dit aan naar wens */
            height: 300px;           /* Geef de container een vaste hoogte */
            overflow-x: auto;        /* Zorgt voor de horizontale scrollbar */
            overflow-y: hidden;      /* Verbergt verticale scroll */
            gap: 16px;               /* Ruimte tussen de foto's */
}
        .scroll-container img {
            height: 100%;            /* Vul de volledige hoogte van de container */
            width: auto;             /* Behoud de originele breedte-verhouding */
            object-fit: cover;       /* Zorgt dat de foto mooi schaalt zonder te vervormen */
            flex-shrink: 0;          /* Voorkomt dat foto's worden samengedrukt */
}
        .rechts-boven {
            position: absolute; /* Haalt de foto uit de normale paginastroom */
            top: 10px;          /* Afstand vanaf de bovenkant */
            right: 10px;        /* Afstand vanaf de rechterkant */
            width: 60px;       /* Pas de breedte naar wens aan */
            height: auto;       /* Behoudt de juiste verhoudingen */
}

    </style>
</head>


<img src="logo.jpeg" alt="fantastica logica" class="rechts-boven">


<h1> Fantastic Four </h1>

<p> hovercraft status: non existent </p>

<div class="scroll-container">

<img src="index_disign.jpeg" alt="fantastica indexia">
<img src="disign.jpeg" alt="fantastica disignia">
<img src="disign2.jpeg" alt="fantastica disignia2">
<img src="propelor.jpeg" alt="fantastica propelor">
<img src="propelor2.jpeg" alt="fantastica propelor2">
<img src="disign3.jpeg" alt="fantastica disignia3">
<img src="disign4.jpeg" alt="fantastica disignia4">
</div>
