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
    </style>
</head>

<h1> Fantastic Four </h1>

<p> hovercraft status: non existent </p>

<div class="scroll-container">
<img src="logo.jpeg" alt="fantastica logica" >
<img src="index_disign.jpeg" alt="fantastica indexia">
<img src="disign.jpeg" alt="fantastica disignia">
<img src="disign2.jpeg" alt="fantastica disignia2">
<img src="propelor.jpeg" alt="fantastica propelor">
<img src="propelor2.jpeg" alt="fantastica propelor2">
</div>
