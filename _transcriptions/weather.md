---
layout: single
title: Weather (Gospel Reprise) - Lawrence
---

[Original audio](https://youtu.be/M9TYHOARDFI?t=188)
/
[SoundSlice](https://www.soundslice.com/slices/Dk7yc/)


<div id="osmd-canvas"></div>

<script>
    window.onload = (event) => {
        console.log("test");
        var osmd = new opensheetmusicdisplay.OpenSheetMusicDisplay("osmd-canvas", {
            autoResize: true, // just an example for an option, no option is necessary.
            backend: "svg",
            drawTitle: false,
            drawingParameters: "compacttight",
        });
        var loadPromise = osmd.load("Weather-Gospel-Reprise.xml");
        loadPromise.then(function(){
            osmd.render();
        });
    };
</script>


