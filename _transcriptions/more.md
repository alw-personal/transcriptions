---
layout: single
title: More (live intro) - Lawrence
---

[Original audio](https://www.youtube.com/watch?v=3VxQsuj2Ee0)
/
[SoundSlice](https://www.soundslice.com/slices/Rdrkc/)


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
        var loadPromise = osmd.load("More-intro.xml");
        loadPromise.then(function(){
            osmd.render();
        });
    };
</script>


