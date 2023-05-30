---
layout: single
title: Have Yourself A Merry Little Christmas - Sarah Paik
---

[Original audio](https://www.youtube.com/watch?v=0dGrAMBfxTY&t=4s)
/
[SoundSlice](https://www.soundslice.com/slices/HwhDc/)


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
        var loadPromise = osmd.load("Have-Yourself-A-Merry-Little-Christmas.xml");
        loadPromise.then(function(){
            osmd.render();
        });
    };
</script>


