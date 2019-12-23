


<!DOCTYPE html>
<html>
<head>
    <meta charset="utf-8">
    <meta content="width=device-width, initial-scale=1.0, maximum-scale=1.0, user-scalable=no" name="viewport">
    <title>GitPitch Slide Deck</title>
    <meta name="description" content="The Markdown Presentation Service on Git.">
    <meta name="keywords" content="Markdown, Presentation, Slideshow, Developer, Git, GitHub, GitLab, Bitbucket, PITCHME">
    <meta name="apple-mobile-web-app-status-bar-style" content="black-translucent">

    

<meta name="twitter:card" content="summary_large_image">
<meta name="twitter:site" content="@gitpitch">
<meta name="twitter:title" content="GitPitch Slide Deck">
<meta name="twitter:description" content="Modern Slide Decks for Developers on Linux, OSX, Windows 10. Present offline. Share online. Export to PPTX and PDF.">
<meta name="twitter:image" content="https://gitpitch.com/gpimg/gitpitch-modern-slide-decks.png">


    

<meta property="og:site_name" content="GitPitch" />
<meta property="og:type" content="article" />
<meta property="og:title" content="GitPitch Slide Deck" />
<meta property="og:description" content="Modern Slide Decks for Developers on Linux, OSX, Windows 10. Present offline. Share online. Export to PPTX and PDF." />
<meta property="og:image" content="https://gitpitch.com/gpimg/gitpitch-modern-slide-decks.png" />
<meta property="og:url" content="https://gitpitch.com/tlaothong/csharp101/conditional?grs=github&amp;t=template" />


    

<link rel="alternate" type="application/json+oembed" href='https://gitpitch.com/pitchme/oembed?url=https%3A%2F%2Fgitpitch.com%2Ftlaothong%2Fcsharp101%2Fconditional%3Fgrs%3Dgithub%26t%3Dtemplate&amp;format=json' title="GitPitch - Markdown Presentations for Everyone on Git" />
<link rel="alternate" type="text/xml+oembed" href='https://gitpitch.com/pitchme/oembed?url=https%3A%2F%2Fgitpitch.com%2Ftlaothong%2Fcsharp101%2Fconditional%3Fgrs%3Dgithub%26t%3Dtemplate&amp;format=xml' title="GitPitch - Markdown Presentations for Everyone on Git" />


    
    
<link href="/assets/libs/reveal.js/3.8.0/css/reveal.css" rel="stylesheet" type="text/css"/>


<link href="/assets/libs/reveal.js/3.8.0/css/theme/beige.css" rel="stylesheet" type="text/css" id="theme"/>
<link href="/assets/libs/css/future.css" rel="stylesheet" type="text/css"/>


<link href="/assets/libs/reveal.js/3.8.0/plugin/title-footer/title-footer-mod.css" rel="stylesheet" type="text/css" id="theme"/>

<link href="/assets/libs/reveal.js/3.8.0/css/print/paper.css" rel="stylesheet" type="text/css"/>


<link href="/assets/libs/highlight.js/9.15.8/github-gist.css" rel="stylesheet" type="text/css"/>
<link href="/assets/libs/octicons/3.5.0/octicons.css" rel="stylesheet" type="text/css"/>
<link href="/assets/libs/font-awesome/5.7.2/css/fa-all.min.css" rel="stylesheet" type="text/css"/>
<link href="/assets/libs/font-awesome/5.7.2/css/fa-v4-shims.min.css" rel="stylesheet" type="text/css"/>

<link href="/assets/libs/css/pitchcore.css" rel="stylesheet" type="text/css"/>




<link href="/assets/libs/css/pitch.css" rel="stylesheet" type="text/css"/>

<link href="/assets/libs/css/pitchmenu.css" rel="stylesheet" type="text/css"/>



<link href="/assets/libs/css/pitchbarlight.css" rel="stylesheet" type="text/css"/>


<link href="/assets/libs/css/pitchcode.css" rel="stylesheet" type="text/css"/>



<link href="https://fonts.googleapis.com/css?family=Roboto" rel="stylesheet">


    

<style>
/*
 * GitPitch Slideshow Custom CSS Styling
 *
 * For details, visit Wiki:
 * https://github.com/gitpitch/gitpitch/wiki/Slideshow-Custom-CSS
 */

body {
  background: #fff;
  background-color: #fff;
}

html:-webkit-full-screen-ancestor {
  background: #fff;
  background-color: #fff;
}

html:-moz-full-screen-ancestor {
  background: #fff;
  background-color: #fff;
}

.reveal pre {
  width: 100%;
  box-shadow : none;
}

.reveal pre code {
  font-size: 1.2em;
  line-height: 1.2;
  max-height: 50vh !important;
  opacity: 0.85;
  border-radius: 10px;
}

.reveal .slides section .code-presenting-annotation {
  color: white;
  background: #1f1c18;
  padding: 1px 15px;
  border-radius: 15px;
  opacity: 0.75 !important;
  font-size: 50% !important;
}

.reveal p span.slide-title {
  color: #333;
  padding: 4px 15px;
  opacity: 0.75 !important;
  border-radius: 15px;
}

.reveal div.left {
    float: left;
    z-index: -10;
    width: 45%;
}

.reveal div.right {
    float: right;
    z-index: -10;
    width: 55%;
}

.reveal a.pro-link {
    font-size: 0.5em;
}

#gp-logo img {
  max-height: 2em;
  max-width: none;
}

.white {
  color: white;
}

.gp-tip { font-size : 1.5em; }

.gp-contact { font-size : 1.4em; }

.gp-download { margin-left: 10px; }


</style>


    <link href="/assets/libs/css/pitchpost.css" rel="stylesheet" type="text/css"/>
    

    
        
            

<script>
  (function(i,s,o,g,r,a,m){i['GoogleAnalyticsObject']=r;i[r]=i[r]||function(){
  (i[r].q=i[r].q||[]).push(arguments)},i[r].l=1*new Date();a=s.createElement(o),
  m=s.getElementsByTagName(o)[0];a.async=1;a.src=g;m.parentNode.insertBefore(a,m)
  })(window,document,'script','https://www.google-analytics.com/analytics.js','ga');
  
  ga('create', 'UA-80973712-1', 'auto');
  ga('send', 'pageview');
  
</script>


        
        
    


</head>
<body>
    

<div id="gp-logo" style="position: fixed; top: 20px; left: 20px; z-index: 1">
    
    <img src="https://gitpitch.com/pitchme/cdn/github/tlaothong/csharp101/conditional/372FDA96478E12B4F260D978B05E596D3C38E5103D7625CFAB190DDC56B4299895D3D9E34B4F9B21F99B2897D633463879BC805BE8C067A4B4924CA77CC7F618136E472450F0E54479477883E839F0E4445F271906E4F9D52916CC681C63ECFA/assets/image/logo.png"/>
    
</div>


    <div class="reveal">
        <div class="slides">
            
            <section data-markdown="/pitchme/markdown/github/tlaothong/csharp101/conditional/PITCHME.md?nonce=372FDA96478E12B4F260D978B05E596D3C38E5103D7625CFAB190DDC56B4299895D3D9E34B4F9B21F99B2897D633463879BC805BE8C067A4B4924CA77CC7F618136E472450F0E54479477883E839F0E4445F271906E4F9D52916CC681C63ECFA"
                     data-separator="(^---$|^---\?.*)"
                     data-separator-vertical="(^\+\+\+$|^\+\+\+\?.*)"
                     data-separator-notes="^Note:"
                     data-charset="utf-8">
            </section>
            
        </div>
        

<footer id="title-footer"><p id="notification"></p></footer>


    </div>
    
    
    <div class="gp-menu"></div>
    
    

    <script src="/assets/libs/reveal.js/3.8.0/js/reveal.js"></script>
    <script src="/assets/libs/jquery/2.2.4/jquery.min.js"></script>
    
    

    <script>
        Reveal.initialize({
            
            controls: true,
            
            controlsLayout: 'bottom-right',
            progress: true,
            embedded: true,
            
            margin: 0.0,
            showNotes: false,
            transition: 'none',
            backgroundTransition: 'none',
            autoSlide: 0,
            loop: false,
            center: true,
            rtl: false,
            shuffle: false,
            mouseWheel: false,
            
            controlsTutorial: true,
            
            
            
              slideNumber: 'c/t', // slideNumber: false,
            
            history: true,
            
            
            menu: {
              custom: [
                
                { title: 'Home', active: true,
                  icon: '<i class="fa fa-bookmark">',
                  src: '/pitchme/home/github/tlaothong/csharp101/conditional/template?offline=false' },
                
              ],
              path : "/assets/libs/reveal.js/3.8.0/plugin/menu",
              themes : false,
              transitions:  false,
              markers: true,
              sticky: true,
              autoOpen: true
            },
            
            
            dependencies: [
                { src: "/assets/libs/reveal.js/3.8.0/plugin/markdown/marked.js",
                  condition: function() {
                    return !!document.querySelector( '[data-markdown]' );
                  }},
                { src: "/assets/libs/reveal.js/3.8.0/plugin/markdown/markdown.js",
                condition: function() {
                  return !!document.querySelector( '[data-markdown]' );
                }},
                
                { src:"/assets/libs/reveal.js/3.8.0/plugin/menu/menu-mod.js",
                  async: true},
                
                
                
                { src: "/assets/libs/reveal.js/3.8.0/plugin/notes/notes.js",
                  async: true },
                
                
                { src: '/assets/libs/highlight.js/9.15.8/highlight.js', async: true },
                { src: '/assets/libs/highlight.js/9.15.8/reveal-code-focus-0619-mod.js',
                  async: true,
                  callback: function() {
                    RevealCodeFocus();
                  }
                },
                
                
                
                
            ]
        });

        Reveal.addEventListener('ready', function(evt) {

          if(typeof twtter !== "undefined") {
              twttr.widgets.load();
          }

          upgradeAnchors();

          if (evt.indexh === 0 && evt.indexv === 0) {
            pushHelpNotification();
          } else {
            pushFootnoteNotification();
          }

          // Force refresh to workaround Reveal.js 3.8.0
          // first render problem re. scrollHeight calc
          // for slides with non-text (image) content.
          setTimeout(Reveal.layout, 500);
        });

        
        Reveal.addEventListener('menu-ready', function(evt) {
            manageMenuPolicy();
        });
        

        Reveal.addEventListener('slidechanged', function(evt) {
          if (evt.indexh === 0 && evt.indexv === 0) {
            pushHelpNotification();
          } else {
            pushFootnoteNotification();
          }
        });

        Reveal.configure({
            keyboard: {
                88: function() { // bind "x" key to "select" code block content

                    var currentSlide = Reveal.getCurrentSlide();
                    var preBlock = $(currentSlide).find("pre");

                    if(preBlock.length > 0) {

                        if (window.getSelection) {
                            var range = document.createRange();
                            range.selectNodeContents(preBlock[0]);
                            var selection = window.getSelection();
                            selection.removeAllRanges();
                            selection.addRange(range);
                        }
                    }
                }
            }
        });

        function enterFullscreen() {
            Reveal.triggerKey(70);
        };

        function enterOverview() {
            Reveal.toggleOverview();
        };

        function enterBlackout() {
            Reveal.togglePause();
        };

        function enterHelp() {
          Reveal.toggleHelp();
        }

        function enableEvents() {
            Reveal.addEventListeners();
        };

        function disableEvents() {
            Reveal.removeEventListeners();
        };

        function manageMenuPolicy() {
            if(RevealMenu && RevealMenu.isOpen()) {
                RevealMenu.toggle();
            }
        }

        function upgradeAnchors() {
            Array.from(document.getElementsByTagName('a')).forEach($link => {
              if ($link.hostname !== window.location.hostname) {
                $link.setAttribute('rel', 'noopener noreferrer');
                $link.setAttribute('target', '_blank');
              }
            });
        }

    </script>

    

    

<script>
    function pushNotification(msg, fade) {
      var footer = document.getElementById('title-footer')
      var notification = document.getElementById('notification')
      if(window.innerWidth < 700) {
        footer.className = "footer-hidden";
      } else {
          footer.className = "footer-visible";
          if(fade) {
            notification.className = "footer-fade";
            notification.innerHTML = msg;
          } else {
            notification.className = "footer-hard";
            notification.innerHTML = msg;
          }
      }
    };

    function pushHelpNotification() {
      if(window.innerWidth < 700)
        pushNotification("<a href='#' onclick='RevealMenu.toggle()'>Menu</a> | <a href='#' onclick='enterFullscreen()'>Fullscreen</a> | <a href='#' onclick='enterOverview()'>Overview</a> | <a href='#' onclick='enterBlackout()'>Blackout</a> | <a href='#' onclick='RevealNotes.open()'>Speaker</a> | <a href='#' onclick='enterHelp()'>Help</a>");
      else
        pushNotification("Navigate : Space / Arrow Keys | <a href='#' onclick='RevealMenu.toggle()'>M</a> - Menu | <a href='#' onclick='enterFullscreen()'>F</a> - Fullscreen | <a href='#' onclick='enterOverview()'>O</a> - Overview | <a href='#' onclick='enterBlackout()'>B</a> - Blackout | <a href='#' onclick='RevealNotes.open()'>S</a> - Speaker | <a href='#' onclick='enterHelp()'>?</a> - Help");
    }

    function pushFootnoteNotification() {
      
        pushNotification("GitPitch [ White Binary ] Presentation Template", true);
      
    }

    function pushCodePresentingStepNotification(step, frags) {
      pushNotification("Code Presenting - Step " + step + " / " + frags, true);
    }
</script>



</body>
</html>
