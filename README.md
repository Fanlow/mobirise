<section class="header7" group="Headers" data-bg-video="{{bg.type == 'video' && bg.value.url}}" mbr-class="{
         'mbr-fullscreen': fullScreen,
         'mbr-parallax-background': bg.parallax}">

    <mbr-parameters>
    <!-- Block parameters controls (Blue "Gear" panel) -->
        <input type="range" inline title="Top" name="paddingTop" min="0" max="9" step="1" value="6">
        <input type="range" inline title="Bottom" name="paddingBottom" min="0" max="9" step="1" value="0">
        <input type="checkbox" title="Show Title" name="showTitle" checked>
        <input type="checkbox" title="Show Text" name="showText" checked>
        <input type="checkbox" title="Show Buttons" name="showButtons" checked>
        <input type="checkbox" title="Content on Left/Right" name="reverseContent">
        <input type="range" inline title="Content Size" name="mediaSize" min="10" max="100" step="5" value="60">
        <input type="color" title="Color Column1" name="colorCol1" value="#4284df">
        <input type="color" title="Color Column2" name="colorCol2" value="#04367c">
        <input type="color" title="Color Column3" name="colorCol3" value="#0c57bf">
        <fieldset type="background" name="bg" parallax>
            <input type="image" title="Background Image" value="file:///C:/Users/mcdra/AppData/Local/Mobirise.com/Mobirise/projects/project-2017-12-04_214534/assets/images/istock_000068400861_medium-1713x1121.jpg" selected parallax>
            <input type="color" title="Background Color" value="#073B4C">
            <input type="video" title="Background Video" value="https://www.youtube.com/watch?v=E0Pa8tYo94U">
        </fieldset>
        <input type="color" title="Bottom Background Color" name="bottomBgColor" value="#4284df">
        <input type="checkbox" title="Overlay" name="overlay" condition="bg.type !== 'color'" checked>
        <input type="color" title="Overlay Color" name="overlayColor" value="#000000" condition="overlay && bg.type !== 'color'">
        <input type="range" inline title="Opacity" name="overlayOpacity" min="0" max="1" step="0.1" value="0.2" condition="overlay && bg.type !== 'color'">
    <!-- End block parameters -->
    </mbr-parameters>

    <div class="mbr-overlay" mbr-if="overlay && bg.type!== 'color'" mbr-style="{'opacity': overlayOpacity, 'background-color': overlayColor}">
    </div>

    <div class="container">
        <div class="media-container-row">
            <div class="mb-4 content-container" mbr-style="{'width': mediaSize + '%'}">
                <h1 class="mbr-section-title pb-3 mbr-fonts-style" mbr-theme-style="display-1" mbr-if="showTitle">Intelligence, Innovation,<b>&nbsp;</b><br><b>Passion</b></h1>
                <p class="mbr-text pb-3 mbr-fonts-style" mbr-theme-style="display-5" mbr-if="showText" data-app-selector=".mbr-text, .mbr-section-btn">"Outsourcing your social media is as easy as 1, 2, 3."</p>
                <div mbr-buttons mbr-theme-style="display-4" class="mbr-section-btn pb-5" mbr-if="showButtons" data-toolbar="-mbrBtnMove"><a class="btn btn-md btn-primary btn-bgr" href="index.html#header9-v">Learn More</a></div>
            </div>
        </div>
    </div>
    <div class="container-boxes mbr-white">
        <div class="box-item">
            <div class="icon-block-top pb-4">
                <span mbr-icon class="mbr-iconfont mbri-mobile" mbr-theme-style="display-2"></span>
            </div>
            <h4 class="box-item-title pb-3 mbr-fonts-style" data-app-selector=".icon-block-top, .box-item-title" mbr-theme-style="display-5">Flexible Rates</h4>
            <p class="box-item-text mbr-fonts-style" data-app-selector=".box-item-text" mbr-theme-style="display-7">We stand behind our services and work to ensure that the value provided far exceeds the your cost of doing business with us.&nbsp;</p>
            <h5 class="mbr-fonts-style" mbr-theme-style="display-5">469-270-6172</h5>
        </div>
        <div class="box-item">
            <div class="icon-block-top pb-4">
                <span mbr-icon class="mbr-iconfont mbri-rocket" mbr-theme-style="display-2"></span>
            </div>
            <h4 class="box-item-title pb-3 mbr-fonts-style" data-app-selector=".icon-block-top, .box-item-title" mbr-theme-style="display-5">Social Media Services</h4>
            <p class="box-item-text mbr-fonts-style" data-app-selector=".box-item-text" mbr-theme-style="display-7">Fanlow social media services are designed to generate greater exposure, followers and a return on your investment (ROI).&nbsp;</p>
        </div>
        <div class="box-item">
            <div class="icon-block-top pb-4">
                <span mbr-icon class="mbr-iconfont mbri-clock" mbr-theme-style="display-2"></span>
            </div>
            <h4 class="box-item-title pb-3 mbr-fonts-style" data-app-selector=".icon-block-top, .box-item-title" mbr-theme-style="display-5">Opening Hours</h4>
            <ul class="box-list" data-multiline mbr-article>
                <li class="clearfix">Monday - Friday<span>10.00-6.00</span></li>
                <li class="clearfix">Saturday<span>10.30-2.30</span></li>
                <li class="clearfix">Sunday<span>CLOSED</span></li>
            </ul>
        </div>
    </div>
</section>
