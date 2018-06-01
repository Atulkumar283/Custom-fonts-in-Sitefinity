# Custom-fonts-in-Sitefinity
How to use custom fonts in Sitefinity CMS

Hey, guys! I am working on a project on Sitefinity CMS. The project requires the use of custom fonts. Custom fonts do not work in Sitefinity CMS in the usual way, so I will show you how to make them work. First, you will need to make a folder named "font" inside the "template" folder. In this folder, you can copy your custom font files in SVG, TTF, WOFF or EOT formats. I have tested this method, and it works in all major browsers (Mozilla Firefox, Google Chrome and Apple Safari).

~/App_Data/Sitefinity/WebsiteTemplate/template/App_theme/theme/global/Fonts

@font-face { font-family: 'Conv_NettoOT';<br>
src: url('fonts/NettoOT.eot');
src: local('☺'),
url('fonts/NettoOT.woff') format('woff'),
url('fonts/NettoOT.ttf') format('truetype'),
url('fonts/NettoOT.svg') format('svg');
font-weight: normal;
font-style: normal;
