
<!DOCTYPE HTML>
<html lang="en">
  <head>
  <head>
    <meta http-equiv="Content-Type" content="text/html; charset=UTF-8">

    <title>Shubham Pateria</title>

    <meta name="author" content="Shubham Pateria">
    <meta name="viewport" content="width=device-width, initial-scale=1">

    <link rel="stylesheet" type="text/css" href="stylesheet.css">
    <link rel="icon" href="data:image/svg+xml,<svg xmlns=%22http://www.w3.org/2000/svg%22 viewBox=%220 0 100 100%22><text y=%22.9em%22 font-size=%2290%22>🌐</text></svg>">
  </head>

  <body>
    <table style="width:100%;max-width:800px;border:0px;border-spacing:0px;border-collapse:separate;margin-right:auto;margin-left:auto;"><tbody>
      <tr style="padding:0px">
        <td style="padding:0px">
          <table style="width:100%;border:0px;border-spacing:0px;border-collapse:separate;margin-right:auto;margin-left:auto;"><tbody>
            <tr style="padding:0px">
              <td style="padding:2.5%;width:63%;vertical-align:middle">
                <p class="name" style="text-align: center;">
                  Jon Barron
                </p>
                <p>I am a senior staff research scientist at <a href="https://ai.google/research">Google Research</a> in <a href="https://en.wikipedia.org/wiki/One_Market_Plaza">San Francisco</a>, where I work on computer vision and machine learning.
                </p>
                <p>
                  At Google I've worked on <a href="https://www.google.com/glass/start/">Glass</a>,  <a href="https://ai.googleblog.com/2014/04/lens-blur-in-new-google-camera-app.html">Lens Blur</a>, <a href="https://ai.googleblog.com/2014/10/hdr-low-light-and-high-dynamic-range.html">HDR+</a>, <a href="https://blog.google/products/google-ar-vr/introducing-next-generation-jump/">Jump</a>, <a href="https://ai.googleblog.com/2017/10/portrait-mode-on-pixel-2-and-pixel-2-xl.html">Portrait Mode</a>, <a href="https://ai.googleblog.com/2020/12/portrait-light-enhancing-portrait.html">Portrait Light</a>, and <a href="https://www.matthewtancik.com/nerf">NeRF</a>. I did my PhD at <a href="http://www.eecs.berkeley.edu/">UC Berkeley</a>, where I was advised by <a href="http://www.cs.berkeley.edu/~malik/">Jitendra Malik</a> and funded by the <a href="http://www.nsfgrfp.org/">NSF GRFP</a>. I've received the <a href="https://www2.eecs.berkeley.edu/Students/Awards/15/">C.V. Ramamoorthy Distinguished Research Award</a> and the <a href="https://www.thecvf.com/?page_id=413#YRA">PAMI Young Researcher Award</a>.
                </p>
                <p style="text-align:center">
                  <a href="mailto:jonbarron@gmail.com">Email</a> &nbsp;/&nbsp;
                  <a href="data/JonBarron-CV.pdf">CV</a> &nbsp;/&nbsp;
                  <a href="data/JonBarron-bio.txt">Bio</a> &nbsp;/&nbsp;
                  <a href="https://scholar.google.com/citations?hl=en&user=jktWnL8AAAAJ">Google Scholar</a> &nbsp;/&nbsp;
                  <a href="https://twitter.com/jon_barron">Twitter</a> &nbsp;/&nbsp;
                  <a href="https://github.com/jonbarron/">Github</a>
                </p>
              </td>
              <td style="padding:2.5%;width:40%;max-width:40%">
                <a href="images/JonBarron.jpg"><img style="width:100%;max-width:100%" alt="profile photo" src="images/shubhamp.jpg" class="hoverZoomLink"></a>
              </td>
            </tr>
          </tbody></table>
          <table style="width:100%;border:0px;border-spacing:0px;border-collapse:separate;margin-right:auto;margin-left:auto;"><tbody>
              <tr>
              <td style="padding:20px;width:100%;vertical-align:middle">
                <h2>Research</h2>
                <p>
                  I'm interested in computer vision, machine learning, optimization, and image processing. Much of my research is about inferring the physical world (shape, motion, color, light, etc) from images. Representative papers are <span class="highlight">highlighted</span>.
                </p>
              </td>
            </tr>
          </tbody></table>
          <table style="width:100%;border:0px;border-spacing:0px;border-collapse:separate;margin-right:auto;margin-left:auto;"><tbody>
          
    
      <tr onmouseout="zipnerf_stop()" onmouseover="zipnerf_start()"  bgcolor="#ffffd0">
        <td style="padding:20px;width:25%;vertical-align:middle">
          <div class="one">
            <div class="two" id='zipnerf_image'><video  width=100% height=100% muted autoplay loop>
            <source src="images/zipnerf.mp4" type="video/mp4">
            Your browser does not support the video tag.
            </video></div>
            <img src='images/zipnerf.jpg' width="160">
          </div>
          <script type="text/javascript">
            function zipnerf_start() {
              document.getElementById('zipnerf_image').style.opacity = "1";
            }

            function zipnerf_stop() {
              document.getElementById('zipnerf_image').style.opacity = "0";
            }
            zipnerf_stop()
          </script>
        </td>
        <td style="padding:20px;width:75%;vertical-align:middle">
          <a href="http://jonbarron.info/zipnerf">
            <span class="papertitle">Zip-NeRF: Anti-Aliased Grid-Based Neural Radiance Fields</span>
          </a>
          <br>
          <strong>Jonathan T. Barron</strong>,
          <a href="https://bmild.github.io/">Ben Mildenhall</a>,
          <a href="https://scholar.harvard.edu/dorverbin/home">Dor Verbin</a>,
          <a href="https://pratulsrinivasan.github.io/">Pratul Srinivasan</a>,
          <a href="https://phogzone.com/">Peter Hedman</a>
          <br>
          <em>ICCV</em>, 2023 &nbsp <font color="red"><strong>(Oral Presentation)</strong></font>
          <br>
          <a href="http://jonbarron.info/zipnerf">project page</a>
          /
          <a href="https://www.youtube.com/watch?v=xrrhynRzC8k">video</a>
          /
          <a href="https://arxiv.org/abs/2304.06706">arXiv</a>
          <p></p>
          <p>
          Combining mip-NeRF 360 and grid-based models like Instant NGP lets us reduce error rates by 8%&ndash;77% and accelerate training by 24x.
          </p>
        </td>
      </tr>
      
      
      <tr onmouseout="db3d_stop()" onmouseover="db3d_start()">
        <td style="padding:20px;width:25%;vertical-align:middle">
          <div class="one">
            <div class="two" id='db3d_image'><video  width=100% height=100% muted autoplay loop>
            <source src="images/owl.mp4" type="video/mp4">
            Your browser does not support the video tag.
            </video></div>
            <img src='images/owl.png' width="160">
          </div>
          <script type="text/javascript">
            function db3d_start() {
              document.getElementById('db3d_image').style.opacity = "1";
            }

            function db3d_stop() {
              document.getElementById('db3d_image').style.opacity = "0";
            }
            db3d_stop()
          </script>
        </td>
        <td style="padding:20px;width:75%;vertical-align:middle">
          <a href="https://dreambooth3d.github.io/">
            <span class="papertitle">DreamBooth3D: Subject-Driven Text-to-3D Generation</span>
          </a>
          <br>
          
  <a href="https://amitraj93.github.io/">Amit Raj</a>, <a href="https://www.linkedin.com/in/srinivas-kaza-64223b74">Srinivas Kaza</a>, <a href="https://poolio.github.io/">Ben Poole</a>, <a href="https://m-niemeyer.github.io/">Michael Niemeyer</a>, <a href="https://natanielruiz.github.io/">Nataniel Ruiz</a>, 
  <a href="https://bmild.github.io/">Ben Mildenhall</a>, <a href="https://scholar.google.com/citations?user=I2qheksAAAAJ">Shiran Zada</a>, <a href="https://kfiraberman.github.io/">Kfir Aberman</a>, <a href="http://people.csail.mit.edu/mrub/">Michael Rubinstein</a>, 
          <strong>Jonathan T. Barron</strong>, <a href="http://people.csail.mit.edu/yzli/">Yuanzhen Li</a>, <a href="https://varunjampani.github.io/">Varun Jampani</a>
          <br>
          <em>ICCV</em>, 2023
          <br>
          <a href="https://dreambooth3d.github.io/">project page</a> / 
          <a href="https://arxiv.org/abs/2303.13508">arXiv</a>
          <p></p>
          <p>Combining DreamBooth (personalized text-to-image) and DreamFusion (text-to-3D) yields high-quality, subject-specific 3D assets with text-driven modifications</p>
        </td>
      </tr>

      

      <tr onmouseout="bakedsdf_stop()" onmouseover="bakedsdf_start()">
        <td style="padding:20px;width:25%;vertical-align:middle">
          <div class="one">
            <div class="two" id='bakedsdf_image'><video  width=100% height=100% muted autoplay loop>
            <source src="images/bakedsdf_after.mp4" type="video/mp4">
            Your browser does not support the video tag.
            </video></div>
            <img src='images/bakedsdf_before.jpg' width="160">
          </div>
          <script type="text/javascript">
            function bakedsdf_start() {
              document.getElementById('bakedsdf_image').style.opacity = "1";
            }

            function bakedsdf_stop() {
              document.getElementById('bakedsdf_image').style.opacity = "0";
            }
            bakedsdf_stop()
          </script>
        </td>
        <td style="padding:20px;width:75%;vertical-align:middle">
          <a href="https://bakedsdf.github.io/">
            <span class="papertitle">BakedSDF: Meshing Neural SDFs for Real-Time View Synthesis</span>
          </a>
          <br>
          <a href="https://lioryariv.github.io/">Lior Yariv*</a>,
          <a href="https://phogzone.com/">Peter Hedman*</a>,
          <a href="https://creiser.github.io/">Christian Reiser</a>,
          <a href="https://dorverbin.github.io/">Dor Verbin</a>,  <br>
          <a href="https://pratulsrinivasan.github.io/">Pratul Srinivasan</a>,
          <a href="https://szeliski.org/RichardSzeliski.htm">Richard Szeliski</a>,
          <strong>Jonathan T. Barron</strong>,
          <a href="https://bmild.github.io/">Ben Mildenhall</a>
          <br>
          <em>SIGGRAPH</em>, 2023
          <br>
          <a href="https://bakedsdf.github.io/">project page</a>
          /
          <a href="https://www.youtube.com/watch?v=fThKXZ6uDTk">video</a>
          /
          <a href="https://arxiv.org/abs/2302.14859">arXiv</a>
          <p></p>
          <p>
          We use SDFs to bake a NeRF-like model into a high quality mesh and do real-time view synthesis.
          </p>
        </td>
      </tr>


      <tr onmouseout="merf_stop()" onmouseover="merf_start()">
        <td style="padding:20px;width:25%;vertical-align:middle">
          <div class="one">
            <div class="two" id='merf_image'><video  width=100% height=100% muted autoplay loop>
            <source src="images/merf_after.mp4" type="video/mp4">
            Your browser does not support the video tag.
            </video></div>
            <img src='images/merf_before.jpg' width="160">
          </div>
          <script type="text/javascript">
            function merf_start() {
              document.getElementById('merf_image').style.opacity = "1";
            }

            function merf_stop() {
              document.getElementById('merf_image').style.opacity = "0";
            }
            merf_stop()
          </script>
        </td>
        <td style="padding:20px;width:75%;vertical-align:middle">
          <a href="https://merf42.github.io/">
            <span class="papertitle">MERF: Memory-Efficient Radiance Fields for Real-time View Synthesis in Unbounded Scenes</span>
          </a>
          <br>
          <a href="https://creiser.github.io/">Christian Reiser</a>,
          <a href="https://szeliski.org/RichardSzeliski.htm">Richard Szeliski</a>,
          <a href="https://dorverbin.github.io/">Dor Verbin</a>,
          <a href="https://pratulsrinivasan.github.io/">Pratul Srinivasan</a>, <br>
          <a href="https://bmild.github.io/">Ben Mildenhall</a>,
          <a href="https://www.cvlibs.net/">Andreas Geiger</a>,
          <strong>Jonathan T. Barron</strong>,
          <a href="https://phogzone.com/">Peter Hedman</a>
          <br>
          <em>SIGGRAPH</em>, 2023
          <br>
          <a href="https://merf42.github.io/">project page</a>
          /
          <a href="https://www.youtube.com/watch?v=3EACM2JAcxc">video</a>
          /
          <a href="https://arxiv.org/abs/2302.12249">arXiv</a>
          <p></p>
          <p>
          We use volumetric rendering with a sparse 3D feature grid and 2D feature planes to do real-time view synthesis.
          </p>
        </td>
      </tr>


      <tr onmouseout="eclipse_stop()" onmouseover="eclipse_start()">
        <td style="padding:20px;width:25%;vertical-align:middle">
          <div class="one">
            <div class="two" id='eclipse_image'><video  width=100% height=100% muted autoplay loop>
            <source src="images/eclipse_after.mp4" type="video/mp4">
            Your browser does not support the video tag.
            </video></div>
            <img src='images/eclipse_before.jpg' width="160">
          </div>
          <script type="text/javascript">
            function eclipse_start() {
              document.getElementById('eclipse_image').style.opacity = "1";
            }

            function eclipse_stop() {
              document.getElementById('eclipse_image').style.opacity = "0";
            }
            eclipse_stop()
          </script>
        </td>
        <td style="padding:20px;width:75%;vertical-align:middle">
          <a href="https://dorverbin.github.io/eclipse">
            <span class="papertitle">Eclipse: Disambiguating Illumination and Materials using Unintended Shadows</span>
          </a>
          <br>
          <a href="https://dorverbin.github.io/">Dor Verbin</a>,
          <a href="https://bmild.github.io/">Ben Mildenhall</a>,
          <a href="https://phogzone.com/">Peter Hedman</a>, <br>
          <strong>Jonathan T. Barron</strong>,
          <a href="Todd Zickler">Todd Zickler</a>,
          <a href="https://pratulsrinivasan.github.io/">Pratul Srinivasan</a>
          <br>
          <em>arXiv</em>, 2023
          <br>
          <a href="https://dorverbin.github.io/eclipse">project page</a>
          /
          <a href="https://www.youtube.com/watch?v=amQLGyza3EU">video</a>
          /
          <a href="https://arxiv.org/abs/2305.16321">arXiv</a>
          <p></p>
          <p>
          Shadows cast by unobserved occluders provide a high-frequency cue for recovering illumination and materials.
          </p>
        </td>
      </tr>
    

      <tr onmouseout="alignerf_stop()" onmouseover="alignerf_start()">
        <td style="padding:20px;width:25%;vertical-align:middle">
          <div class="one">
            <div class="two" id='alignerf_image'>
              <img src='images/alignerf_after.jpg' width="160"></div>
            <img src='images/alignerf_before.jpg' width="160">
          </div>
          <script type="text/javascript">
            function alignerf_start() {
              document.getElementById('alignerf_image').style.opacity = "1";
            }

            function alignerf_stop() {
              document.getElementById('alignerf_image').style.opacity = "0";
            }
            alignerf_stop()
          </script>
        </td>
        <td style="padding:20px;width:75%;vertical-align:middle">
          <a href="https://yifanjiang19.github.io/alignerf">
            <span class="papertitle">AligNeRF: High-Fidelity Neural Radiance Fields via Alignment-Aware Training</span>
          </a>
          <br>
          <a href="https://yifanjiang.net/">Yifan Jiang</a>,
          <a href="https://phogzone.com/">Peter Hedman</a>, 
          <a href="https://bmild.github.io/">Ben Mildenhall</a>,
          <a href="https://ir1d.github.io/">Dejia Xu</a>, <br>
          <strong>Jonathan T. Barron</strong>,
          <a href="https://spark.adobe.com/page/CAdrFMJ9QeI2y/">Zhangyang Wang</a>,
          <a href="https://tianfan.info/">Tianfan Xue</a>
          <br>
          <em>CVPR</em>, 2023
          <br>
          <a href="https://yifanjiang19.github.io/alignerf">project page</a>
          /
          <a href="https://arxiv.org/abs/2211.09682">arXiv</a>
          <p></p>
          <p>
          Accounting for misalignment due to scene motion or calibration errors improves NeRF reconstruction quality.
          </p>
        </td>
      </tr>
      
  <tr onmouseout="dreamfusion_stop()" onmouseover="dreamfusion_start()"  bgcolor="#ffffd0">
    <td style="padding:20px;width:25%;vertical-align:middle">
      <div class="one">
        <div class="two" id='dreamfusion_image'><video  width=100% height=100% muted autoplay loop>
        <source src="images/dreamfusion.mp4" type="video/mp4">
        Your browser does not support the video tag.
        </video></div>
        <img src='images/dreamfusion.jpg' width="160">
      </div>
      <script type="text/javascript">
        function dreamfusion_start() {
          document.getElementById('dreamfusion_image').style.opacity = "1";
        }

        function dreamfusion_stop() {
          document.getElementById('dreamfusion_image').style.opacity = "0";
        }
        dreamfusion_stop()
      </script>
    </td>
    <td style="padding:20px;width:75%;vertical-align:middle">
      <a href="https://dreamfusion3d.github.io/">
        <span class="papertitle">DreamFusion: Text-to-3D using 2D Diffusion</span>
      </a>
      <br>
      <a href="https://cs.stanford.edu/~poole/">Ben Poole</a>,
      <a href="https://www.ajayj.com/">Ajay Jain</a>,
      <strong>Jonathan T. Barron</strong>,
      <a href="https://bmild.github.io/">Ben Mildenhall</a>
      <br>
      <em>ICLR</em>, 2023 &nbsp <font color="red"><strong>(Oral Presentation, Outstanding Paper Award)</strong></font>
      <br>
      <a href="https://dreamfusion3d.github.io/">project page</a>
      /
      <a href="https://arxiv.org/abs/2209.14988">arXiv</a>
      /
      <a href="https://dreamfusion3d.github.io/gallery.html">gallery</a>
      <p></p>
      <p>
      We optimize a NeRF from scratch using a pretrained text-to-image diffusion model to do text-to-3D generative modeling.
      </p>
    </td>
  </tr>

  <tr onmouseout="guandao_stop()" onmouseover="guandao_start()">
  <td style="padding:20px;width:25%;vertical-align:middle">
    <div class="one">
      <div class="two" id='guandao_image'>
        <img src='images/guandao_after.png' width="160"></div>
      <img src='images/guandao_before.png' width="160">
    </div>
    <script type="text/javascript">
      function guandao_start() {
        document.getElementById('guandao_image').style.opacity = "1";
      }

      function guandao_stop() {
        document.getElementById('guandao_image').style.opacity = "0";
      }
      guandao_stop()
    </script>
  </td>
  <td style="padding:20px;width:75%;vertical-align:middle">
    <a href="https://arxiv.org/abs/2304.14473">
      <span class="papertitle">Learning a Diffusion Prior for NeRFs</span>
    </a>
    <br>
    <a href="https://www.guandaoyang.com/">Guandao Yang</a>, 
    <a href="https://abhijitkundu.info/">Abhijit Kundu</a>, 
    <a href="https://geometry.stanford.edu/member/guibas/index.html">Leonidas J. Guibas</a>, 
    <strong>Jonathan T. Barron</strong>, 
    <a href="https://cs.stanford.edu/~poole/">Ben Poole</a>
    <br>
    <em>ICLR Workshop</em>, 2023
    <p></p>
    <p>
      Training a diffusion model on grid-based NeRFs lets you (conditionally) sample NeRFs.
    </p>
  </td>
  </tr>

            <tr onmouseout="mira_stop()" onmouseover="mira_start()">
              <td style="padding:20px;width:25%;vertical-align:middle">
                <div class="one">
                  <div class="two" id='mira_image'>
                    <img src='images/mira_after.jpg' width="160"></div>
                  <img src='images/mira_before.jpg' width="160">
                </div>
                <script type="text/javascript">
                  function mira_start() {
                    document.getElementById('mira_image').style.opacity = "1";
                  }

                  function mira_stop() {
                    document.getElementById('mira_image').style.opacity = "0";
                  }
                  mira_stop()
                </script>
              </td>
              <td style="padding:20px;width:75%;vertical-align:middle">
                <a href="https://openreview.net/forum?id=AmPeAFzU3a4">
                  <span class="papertitle">MIRA: Mental Imagery for Robotic Affordances</span>
                </a>
                <br>
                <a href="https://yenchenlin.me/">Lin Yen-Chen</a>, 
                <a href="http://www.peteflorence.com/">Pete Florence</a>, 
                <a href="https://andyzeng.github.io/">Andy Zeng</a>, <strong>Jonathan T. Barron</strong>, 
                <a href="https://yilundu.github.io/">Yilun Du</a>,
                <a href="https://people.csail.mit.edu/weichium/">Wei-Chiu Ma</a>,
                <a href="https://anthonysimeonov.github.io/">Anthony Simeonov</a>,
                <a href="https://meche.mit.edu/people/faculty/ALBERTOR@MIT.EDU">Alberto Rodriguez</a>,
                <a href="http://web.mit.edu/phillipi/">Phillip Isola</a>
                <br>
                <em>CoRL</em>, 2022
                <p></p>
                <p>
                  NeRF lets us synthesize novel orthographic views that work well with pixel-wise algorithms for robotic manipulation.
                </p>
              </td>
            </tr>		
            
            <tr onmouseout="samurai_stop()" onmouseover="samurai_start()">
              <td style="padding:20px;width:25%;vertical-align:middle">
                <div class="one">
                  <div class="two" id='samurai_image'>
                    <img src='images/samurai_after.jpg' width="160"></div>
                  <img src='images/samurai_before.jpg' width="160">
                </div>
                <script type="text/javascript">
                  function samurai_start() {
                    document.getElementById('samurai_image').style.opacity = "1";
                  }

                  function samurai_stop() {
                    document.getElementById('samurai_image').style.opacity = "0";
                  }
                  samurai_stop()
                </script>
              </td>
              <td style="padding:20px;width:75%;vertical-align:middle">
                <a href="https://markboss.me/publication/2022-samurai/">
                  <span class="papertitle">SAMURAI: Shape And Material from Unconstrained Real-world Arbitrary Image Collections</span>
                </a>
                <br>
                <a href="https://markboss.me">Mark Boss</a>, 
                <a href="">Andreas Engelhardt</a>, 
                <a href="https://abhishekkar.info/">Abhishek Kar</a>, 
                <a href="http://people.csail.mit.edu/yzli/">Yuanzhen Li</a>, 
                <a href="https://deqings.github.io/">Deqing Sun</a>, 
                <strong>Jonathan T. Barron</strong>,
                <a href="https://uni-tuebingen.de/en/faculties/faculty-of-science/departments/computer-science/lehrstuehle/computergrafik/computer-graphics/staff/prof-dr-ing-hendrik-lensch/">Hendrik P. A. Lensch</a>,
                <a href="https://varunjampani.github.io">Varun Jampani</a>
                <br>
                <em>NeurIPS</em>, 2022
                <br>
                <a href="https://markboss.me/publication/2022-samurai/">project page</a> /
                <a href="https://www.youtube.com/watch?v=LlYuGDjXp-8">video</a> /
                <a href="https://arxiv.org/abs/2205.15768">arXiv</a>
                <p></p>
                <p>
  A joint optimization framework for estimating shape, BRDF, camera pose, and illumination from in-the-wild image collections.
                </p>
              </td>
            </tr>		

            <tr onmouseout="pnf_stop()" onmouseover="pnf_start()">
            <td style="padding:20px;width:25%;vertical-align:middle">
            <div class="one">
            <div class="two" id='pnf_image'>
              <img src='images/pnf_before.jpg' width="160"></div>
            <img src='images/pnf_after.jpg' width="160">
            </div>
            <script type="text/javascript">
            function pnf_start() {
              document.getElementById('pnf_image').style.opacity = "1";
            }

            function pnf_stop() {
              document.getElementById('pnf_image').style.opacity = "0";
            }
            pnf_stop()
            </script>
            </td>
            <td style="padding:20px;width:75%;vertical-align:middle">
            <a href="TODO">
            <span class="papertitle">Polynomial Neural Fields for Subband Decomposition</span>
            </a> <br>
            <a href="https://www.guandaoyang.com/">Guandao Yang*</a>,
            <a href="https://sagiebenaim.github.io/">Sagie Benaim*</a>,
            <a href="https://varunjampani.github.io/">Varun Jampani</a>,
            <a href="https://www.kylegenova.com/">Kyle Genova</a>,
            <strong>Jonathan T. Barron</strong>,
            <a href="https://www.cs.princeton.edu/~funk/">Thomas Funkhouser</a>,
            <a href="http://home.bharathh.info/">Bharath Hariharan</a>,
            <a href="https://sergebelongie.github.io/">Serge Belongie</a>
            <br>
            <em>NeurIPS</em>, 2022
            <p>
            Representing neural fields as a composition of manipulable and interpretable components lets you do things like reason about frequencies and scale.
            </p>
            </td>
            </tr> 


            <tr onmouseout="malle_stop()" onmouseover="malle_start()">
              <td style="padding:20px;width:25%;vertical-align:middle">
                <div class="one">
                  <div class="two" id='malle_image'>
                    <img src='images/MalleConv_after.jpg' width="160"></div>
                  <img src='images/MalleConv_before.jpg' width="160">
                </div>
                <script type="text/javascript">
                  function malle_start() {
                    document.getElementById('malle_image').style.opacity = "1";
                  }

                  function malle_stop() {
                    document.getElementById('malle_image').style.opacity = "0";
                  }
                  malle_stop()
                </script>
              </td>
              <td style="padding:20px;width:75%;vertical-align:middle">
                <a href="https://yifanjiang.net/MalleConv.html">
                  <span class="papertitle">Fast and High-Quality Image Denoising via Malleable Convolutions</span>
                </a>
                <br>
                <a href="https://yifanjiang.net/">Yifan Jiang</a>,
                <a href="https://bartwronski.com/">Bartlomiej Wronski</a>, 
                <a href="https://bmild.github.io/">Ben Mildenhall</a>, <br>
                <strong>Jonathan T. Barron</strong>,
                <a href="https://spark.adobe.com/page/CAdrFMJ9QeI2y/">Zhangyang Wang</a>,
                <a href="https://tianfan.info/">Tianfan Xue</a>
                <br>
                <em>ECCV</em>, 2022
                <br>
                <a href="https://yifanjiang.net/MalleConv.html">project page</a>
                /
                <a href="https://arxiv.org/abs/2201.00392">arXiv</a>
                <p></p>
                <p>
                We denoise images efficiently by predicting spatially-varying kernels at low resolution and using a fast fused op to jointly upsample and apply these kernels at full resolution.
                </p>
              </td>
            </tr>
            
            <tr onmouseout="nerfsuper_stop()" onmouseover="nerfsuper_start()">
              <td style="padding:20px;width:25%;vertical-align:middle">
                <div class="one">
                  <div class="two" id='nerfsuper_image'><video  width=100% height=100% muted autoplay loop>
                  <source src="images/nerf_supervision.mp4" type="video/mp4">
                  Your browser does not support the video tag.
                  </video></div>
                  <img src='images/nerf_supervision.jpg' width="160">
                </div>
                <script type="text/javascript">
                  function nerfsuper_start() {
                    document.getElementById('nerfsuper_image').style.opacity = "1";
                  }

                  function nerfsuper_stop() {
                    document.getElementById('nerfsuper_image').style.opacity = "0";
                  }
                  nerfsuper_stop()
                </script>
              </td>
              <td style="padding:20px;width:75%;vertical-align:middle">
                <a href="http://yenchenlin.me/nerf-supervision/">
                  <span class="papertitle">NeRF-Supervision: Learning Dense Object Descriptors from Neural Radiance Fields</span>
                </a>
                <br>
                <a href="https://yenchenlin.me/">Lin Yen-Chen</a>, 
                <a href="http://www.peteflorence.com/">Pete Florence</a>, 
                <strong>Jonathan T. Barron</strong>,  <br>
                <a href="https://scholar.google.com/citations?user=_BPdgV0AAAAJ&hl=en">Tsung-Yi Lin</a>, 
                <a href="https://meche.mit.edu/people/faculty/ALBERTOR@MIT.EDU">Alberto Rodriguez</a>,
                <a href="http://web.mit.edu/phillipi/">Phillip Isola</a>
                <br>
                <em>ICRA</em>, 2022  
                <br>
                <a href="http://yenchenlin.me/nerf-supervision/">project page</a> / 
                <a href="https://arxiv.org/abs/2203.01913">arXiv</a> / 
                <a href="https://www.youtube.com/watch?v=_zN-wVwPH1s">video</a> /
                <a href="https://github.com/yenchenlin/nerf-supervision-public">code</a> / 
                <a href="https://colab.research.google.com/drive/13ISri5KD2XeEtsFs25hmZtKhxoDywB5y?usp=sharing">colab</a>				
                <p></p>
                <p>NeRF works better than RGB-D cameras or multi-view stereo when learning object descriptors.</p>
              </td>
            </tr>

            <tr onmouseout="refnerf_stop()" onmouseover="refnerf_start()"  bgcolor="#ffffd0">
              <td style="padding:20px;width:25%;vertical-align:middle">
                <div class="one">
                  <div class="two" id='refnerf_image'><video  width=100% height=100% muted autoplay loop>
                  <source src="images/refnerf.mp4" type="video/mp4">
                  Your browser does not support the video tag.
                  </video></div>
                  <img src='images/refnerf.jpg' width="160">
                </div>
                <script type="text/javascript">
                  function refnerf_start() {
                    document.getElementById('refnerf_image').style.opacity = "1";
                  }

                  function refnerf_stop() {
                    document.getElementById('refnerf_image').style.opacity = "0";
                  }
                  refnerf_stop()
                </script>
              </td>
                    <td style="padding:20px;width:75%;vertical-align:middle">
                  <a href="https://dorverbin.github.io/refnerf/index.html">
                    <span class="papertitle">Ref-NeRF: Structured View-Dependent Appearance for Neural Radiance Fields</span>
                  </a>
                  <br>
                  <a href="https://scholar.harvard.edu/dorverbin/home">Dor Verbin</a>,
                  <a href="https://phogzone.com/">Peter Hedman</a>,
                  <a href="https://bmild.github.io/">Ben Mildenhall</a>, <br>
                  <a href="Todd Zickler">Todd Zickler</a>,
                  <strong>Jonathan T. Barron</strong>,
                  <a href="https://pratulsrinivasan.github.io/">Pratul Srinivasan</a>
                  <br>
            <em>CVPR</em>, 2022 &nbsp <font color="red"><strong>(Oral Presentation, Best Student Paper Honorable Mention)</strong></font>
                  <br>
                  <a href="https://dorverbin.github.io/refnerf/index.html">project page</a>
            /
                  <a href="https://arxiv.org/abs/2112.03907">arXiv</a>
            /
                  <a href="https://youtu.be/qrdRH9irAlk">video</a>
                  <p></p>
                  <p>Explicitly modeling reflections in NeRF produces realistic shiny surfaces and accurate surface normals, and lets you edit materials.</p>
                </td>
              </tr>
              
            <tr onmouseout="mip360_stop()" onmouseover="mip360_start()"  bgcolor="#ffffd0">
              <td style="padding:20px;width:25%;vertical-align:middle">
                <div class="one">
                  <div class="two" id='mip360_image'><video  width=100% height=100% muted autoplay loop>
                  <source src="images/mip360_sat.mp4" type="video/mp4">
                  Your browser does not support the video tag.
                  </video></div>
                  <img src='images/mip360_sat.jpg' width="160">
                </div>
                <script type="text/javascript">
                  function mip360_start() {
                    document.getElementById('mip360_image').style.opacity = "1";
                  }

                  function mip360_stop() {
                    document.getElementById('mip360_image').style.opacity = "0";
                  }
                  mip360_stop()
                </script>
              </td>
              <td style="padding:20px;width:75%;vertical-align:middle">
                <a href="http://jonbarron.info/mipnerf360">
                  <span class="papertitle">Mip-NeRF 360: Unbounded Anti-Aliased Neural Radiance Fields</span>
                </a>
                <br>
                <strong>Jonathan T. Barron</strong>,
                <a href="https://bmild.github.io/">Ben Mildenhall</a>,
                <a href="https://scholar.harvard.edu/dorverbin/home">Dor Verbin</a>,
                <a href="https://pratulsrinivasan.github.io/">Pratul Srinivasan</a>,
                <a href="https://phogzone.com/">Peter Hedman</a>
                <br>
                <em>CVPR</em>, 2022 &nbsp <font color="red"><strong>(Oral Presentation)</strong></font>
                <br>
                <a href="http://jonbarron.info/mipnerf360">project page</a>
                /
                <a href="https://arxiv.org/abs/2111.12077">arXiv</a>
                /
                <a href="https://youtu.be/zBSH-k9GbV4">video</a>
                <p></p>
                <p>mip-NeRF can be extended to produce realistic results on unbounded scenes.</p>
              </td>
            </tr> 

            <tr onmouseout="rawnerf_stop()" onmouseover="rawnerf_start()"  bgcolor="#ffffd0">
              <td style="padding:20px;width:25%;vertical-align:middle">
                <div class="one">
                  <div class="two" id='rawnerf_image'><video  width=100% height=100% muted autoplay loop>
                  <source src="images/rawnerf.mp4" type="video/mp4">
                  Your browser does not support the video tag.
                  </video></div>
                  <img src='images/rawnerf.jpg' width="160">
                </div>
                <script type="text/javascript">
                  function rawnerf_start() {
                    document.getElementById('rawnerf_image').style.opacity = "1";
                  }

                  function rawnerf_stop() {
                    document.getElementById('rawnerf_image').style.opacity = "0";
                  }
                  rawnerf_stop()
                </script>
              </td>
              <td style="padding:20px;width:75%;vertical-align:middle">
                <a href="https://bmild.github.io/rawnerf/index.html">
                  <span class="papertitle">NeRF in the Dark: High Dynamic Range View Synthesis from Noisy Raw Images</span>
                </a>
                <br>
                <a href="https://bmild.github.io/">Ben Mildenhall</a>,
                <a href="https://phogzone.com/">Peter Hedman</a>,
                <a href="http://www.ricardomartinbrualla.com/">Ricardo Martin-Brualla</a>, <br>
                <a href="https://pratulsrinivasan.github.io/">Pratul Srinivasan</a>,
                <strong>Jonathan T. Barron</strong>
                <br>
                <em>CVPR</em>, 2022 &nbsp <font color="red"><strong>(Oral Presentation)</strong></font>
                <br>
                <a href="https://bmild.github.io/rawnerf/index.html">project page</a>
          /
                <a href="https://arxiv.org/abs/2111.13679">arXiv</a>
          /
                <a href="https://www.youtube.com/watch?v=JtBS4KBcKVc">video</a>
                <p></p>
                <p>
                  Properly training NeRF on raw camera data enables HDR view synthesis and bokeh, and outperforms multi-image denoising.</p>
              </td>
            </tr> 
            
    
            <tr onmouseout="regnerf_stop()" onmouseover="regnerf_start()">
              <td style="padding:20px;width:25%;vertical-align:middle">
                <div class="one">
                  <div class="two" id='regnerf_image'><video  width=100% height=100% muted autoplay loop>
                  <source src="images/regnerf_after.mp4" type="video/mp4">
                  Your browser does not support the video tag.
                  </video></div>
                  <img src='images/regnerf_before.jpeg' width="160">
                </div>
                <script type="text/javascript">
                  function regnerf_start() {
                    document.getElementById('regnerf_image').style.opacity = "1";
                  }

                  function regnerf_stop() {
                    document.getElementById('regnerf_image').style.opacity = "0";
                  }
                  regnerf_stop()
                </script>
              </td>
              <td style="padding:20px;width:75%;vertical-align:middle">
                <a href="https://m-niemeyer.github.io/regnerf/index.html">
                  <span class="papertitle">RegNeRF: Regularizing Neural Radiance Fields for View Synthesis from Sparse Inputs</span>
                </a>
                <br>
                <a href="https://m-niemeyer.github.io/">Michael Niemeyer</a>,
                <strong>Jonathan T. Barron</strong>,
                <a href="https://bmild.github.io/">Ben Mildenhall</a>, <br>
                <a href="https://msmsajjadi.github.io/">Mehdi S. M. Sajjadi</a>, 
                <a href="http://www.cvlibs.net/">Andreas Geiger</a>,
                <a href="http://www2.informatik.uni-freiburg.de/~radwann/">Noha Radwan</a>
                <br>
          <em>CVPR</em>, 2022 &nbsp <font color="red"><strong>(Oral Presentation)</strong></font>
                <br>
                <a href="https://m-niemeyer.github.io/regnerf/index.html">project page</a>
          /
                <a href="https://arxiv.org/abs/2112.00724">arXiv</a>
          /
                <a href="https://www.youtube.com/watch?v=QyyyvA4-Kwc">video</a>
                <p></p>
                <p>Regularizing unseen views during optimization enables view synthesis from as few as 3 input images.</p>
              </td>
            </tr> 


            <tr onmouseout="blocknerf_stop()" onmouseover="blocknerf_start()">
              <td style="padding:20px;width:25%;vertical-align:middle">
                <div class="one">
                  <div class="two" id='blocknerf_image'><video  width=100% height=100% muted autoplay loop>
                  <source src="images/blocknerf_after.mp4" type="video/mp4">
                  Your browser does not support the video tag.
                  </video></div>
                  <img src='images/blocknerf_before.jpg' width="160">
                </div>
                <script type="text/javascript">
                  function blocknerf_start() {
                    document.getElementById('blocknerf_image').style.opacity = "1";
                  }

                  function blocknerf_stop() {
                    document.getElementById('blocknerf_image').style.opacity = "0";
                  }
                  blocknerf_stop()
                </script>
              </td>
              <td style="padding:20px;width:75%;vertical-align:middle">
                <a href="https://waymo.com/research/block-nerf/">
                  <span class="papertitle">Block-NeRF: Scalable Large Scene Neural View Synthesis</span>
                </a>
                <br>
                <a href="http://matthewtancik.com/">Matthew Tancik</a>,
                <a href="http://casser.io/">Vincent Casser</a>,
                <a href="https://sites.google.com/site/skywalkeryxc/">Xinchen Yan</a>,
                <a href="https://scholar.google.com/citations?user=5mJUkI4AAAAJ&hl=en">Sabeek Pradhan</a>, <br>
                <a href="https://bmild.github.io/">Ben Mildenhall</a>,
                <a href="https://pratulsrinivasan.github.io/">Pratul Srinivasan</a>,
                <strong>Jonathan T. Barron</strong>,
                <a href="https://www.henrikkretzschmar.com/">Henrik Kretzschmar</a>
                <br>
          <em>CVPR</em>, 2022 &nbsp <font color="red"><strong>(Oral Presentation)</strong></font>
                <br>
                <a href="https://waymo.com/research/block-nerf/">project page</a>
          /
                <a href="https://arxiv.org/abs/2202.05263">arXiv</a>
          /
                <a href="https://www.youtube.com/watch?v=6lGMCAzBzOQ">video</a>
                <p></p>
                <p>We can do city-scale reconstruction by training multiple NeRFs with millions of images.</p>
              </td>
            </tr>
            
            <tr onmouseout="hnerf_stop()" onmouseover="hnerf_start()">
              <td style="padding:20px;width:25%;vertical-align:middle">
                <div class="one">
                  <div class="two" id='hnerf_image'><video  width=100% height=100% muted autoplay loop>
                  <source src="images/hnerf_after.mp4" type="video/mp4">
                  Your browser does not support the video tag.
                  </video></div>
                  <img src='images/hnerf_before.jpg' width="160">
                </div>
                <script type="text/javascript">
                  function hnerf_start() {
                    document.getElementById('hnerf_image').style.opacity = "1";
                  }

                  function hnerf_stop() {
                    document.getElementById('hnerf_image').style.opacity = "0";
                  }
                  hnerf_stop()
                </script>
              </td>
              <td style="padding:20px;width:75%;vertical-align:middle">
                <a href="https://grail.cs.washington.edu/projects/humannerf/">
                  <span class="papertitle">HumanNeRF: Free-viewpoint Rendering of Moving People from Monocular Video</span>
                </a>
                <br>
                <a href="https://homes.cs.washington.edu/~chungyi/">Chung-Yi Weng</a>,
                <a href="https://homes.cs.washington.edu/~curless/">Brian Curless</a>,
                <a href="https://pratulsrinivasan.github.io/">Pratul Srinivasan</a>, <br>
                <strong>Jonathan T. Barron</strong>,
                <a href="https://www.irakemelmacher.com/">Ira Kemelmacher-Shlizerman </a>
                <br>
                <em>CVPR</em>, 2022 &nbsp <font color="red"><strong>(Oral Presentation)</strong></font>
                <br>
                <a href="https://grail.cs.washington.edu/projects/humannerf/">project page</a>
                /
                <a href="https://arxiv.org/abs/2201.04127">arXiv</a>
                /
                <a href="https://youtu.be/GM-RoZEymmw">video</a>
                <p></p>
                <p>Combining NeRF with pose estimation lets you use a monocular video to do free-viewpoint rendering of a human.</p>
              </td>
            </tr>
            
            <tr onmouseout="urf_stop()" onmouseover="urf_start()">
              <td style="padding:20px;width:25%;vertical-align:middle">
                <div class="one">
                  <div class="two" id='urf_image'><video  width=100% height=100% muted autoplay loop>
                  <source src="images/urf.mp4" type="video/mp4">
                  Your browser does not support the video tag.
                  </video></div>
                  <img src='images/urf.jpg' width="160">
                </div>
                <script type="text/javascript">
                  function urf_start() {
                    document.getElementById('urf_image').style.opacity = "1";
                  }

                  function urf_stop() {
                    document.getElementById('urf_image').style.opacity = "0";
                  }
                  urf_stop()
                </script>
              </td>
              <td style="padding:20px;width:75%;vertical-align:middle">
                <a href="https://urban-radiance-fields.github.io/">
                  <span class="papertitle">Urban Radiance Fields</span>
                </a>
                <br>
                <a href="http://www.krematas.com/">Konstantinos Rematas</a>,
                <a href="https://andrewhliu.github.io/">Andrew Liu</a>,
                <a href="https://pratulsrinivasan.github.io/">Pratul P. Srinivasan</a>,
                <strong>Jonathan T. Barron</strong>, <br>
                <a href="https://taiya.github.io/">Andrea Tagliasacchi</a>,
                <a href="https://www.cs.princeton.edu/~funk/">Tom Funkhouser</a>,
                <a href="https://sites.google.com/corp/view/vittoferrari"> Vittorio Ferrari</a>
                <br>
                <em>CVPR</em>, 2022
                <br>
                <a href="https://urban-radiance-fields.github.io/">project page</a>
                /
                <a href="https://arxiv.org/abs/2111.14643">arXiv</a>
                /
                <a href="https://www.youtube.com/watch?v=qGlq5DZT6uc">video</a>
                <p></p>
                <p>
                  Incorporating lidar and explicitly modeling the sky lets you reconstruct urban environments.</p>
              </td>
            </tr> 

    
    <tr onmouseout="ddp_stop()" onmouseover="ddp_start()">
      <td style="padding:20px;width:25%;vertical-align:middle">
        <div class="one">
          <div class="two" id='ddp_image'>
            <img src='images/ddp_after.jpg' width="160"></div>
          <img src='images/ddp_before.jpg' width="160">
        </div>
        <script type="text/javascript">
          function ddp_start() {
            document.getElementById('ddp_image').style.opacity = "1";
          }

          function ddp_stop() {
            document.getElementById('ddp_image').style.opacity = "0";
          }
          ddp_stop()
        </script>
      </td>
      <td style="padding:20px;width:75%;vertical-align:middle">
        <a href="https://arxiv.org/abs/2112.03288">
          <span class="papertitle">Dense Depth Priors for Neural Radiance Fields from Sparse Input Views</span>
        </a>
        <br>
        <a href="https://niessnerlab.org/members/barbara_roessle/profile.html">Barbara Roessle</a>,
        <strong>Jonathan T. Barron</strong>,
        <a href="https://bmild.github.io/">Ben Mildenhall</a>, 
        <a href="https://pratulsrinivasan.github.io/">Pratul Srinivasan</a>, 
        <a href="https://www.niessnerlab.org/">Matthias Nießner</a>
        <br>
        <em>CVPR</em>, 2022
        <br>
        <a href="https://arxiv.org/abs/2112.03288">arXiv</a>
        /
        <a href="https://www.youtube.com/watch?v=zzkvvdcvksc">video</a>
        <p></p>
        <p>
        Dense depth completion techniques applied to freely-available sparse stereo data can improve NeRF reconstructions in low-data regimes.
        </p>
      </td>
    </tr>
    
            <tr onmouseout="clipnerf_stop()" onmouseover="clipnerf_start()">
              <td style="padding:20px;width:25%;vertical-align:middle">
                <div class="one">
                  <div class="two" id='clipnerf_image'><video  width=100% height=100% muted autoplay loop>
                  <source src="images/dreamfield_after.mp4" type="video/mp4">
                  Your browser does not support the video tag.
                  </video></div>
                  <img src='images/dreamfield_before.jpg' width="160">
                </div>
                <script type="text/javascript">
                  function clipnerf_start() {
                    document.getElementById('clipnerf_image').style.opacity = "1";
                  }

                  function clipnerf_stop() {
                    document.getElementById('clipnerf_image').style.opacity = "0";
                  }
                  clipnerf_stop()
                </script>
              </td>
              <td style="padding:20px;width:75%;vertical-align:middle">
                <a href="https://ajayj.com/dreamfields">
                  <span class="papertitle">Zero-Shot Text-Guided Object Generation with Dream Fields</span>
                </a>
                <br>
                <a href="https://www.ajayj.com/">Ajay Jain</a>,
                <a href="https://bmild.github.io/">Ben Mildenhall</a>,
                <strong>Jonathan T. Barron</strong>,
                <a href="https://people.eecs.berkeley.edu/~pabbeel/">Pieter Abbeel</a>,
                <a href="https://cs.stanford.edu/~poole/">Ben Poole</a>
                <br>
          <em>CVPR</em>, 2022
                <br>
                <a href="https://ajayj.com/dreamfields">project page</a>
          /
                <a href="https://arxiv.org/abs/2112.01455">arXiv</a>
          /
                <a href="https://www.youtube.com/watch?v=1Fke6w46tv4">video</a>
                <p></p>
                <p>Supervising the CLIP embeddings of NeRF renderings lets you to generate 3D objects from text prompts.</p>
              </td>
            </tr> 
      
            <tr onmouseout="survey_stop()" onmouseover="survey_start()">
              <td style="padding:20px;width:25%;vertical-align:middle">
                <div class="one">
                  <div class="two" id='survey_image'>
                    <img src='images/survey_after.png' width="160"></div>
                  <img src='images/survey_before.png' width="160">
                </div>
                <script type="text/javascript">
                  function survey_start() {
                    document.getElementById('survey_image').style.opacity = "1";
                  }

                  function survey_stop() {
                    document.getElementById('survey_image').style.opacity = "0";
                  }
                  survey_stop()
                </script>
              </td>
              <td style="padding:20px;width:75%;vertical-align:middle">
                <a href="https://arxiv.org/abs/2111.05849">
                  <span class="papertitle">Advances in Neural Rendering</span>
                </a>
                <br>
                <a href="https://people.mpi-inf.mpg.de/~atewari/">Ayush Tewari</a>, 
                <a href="https://justusthies.github.io/">Justus Thies</a>, 
                <a href="https://bmild.github.io/">Ben Mildenhall</a>, 
                <a href="https://pratulsrinivasan.github.io/">Pratul Srinivasan</a>, 
                <a href="https://people.mpi-inf.mpg.de/~tretschk/">Edgar Tretschk</a>,
                <a href="https://homes.cs.washington.edu/~yifan1/">Yifan Wang</a>,
                <a href="https://christophlassner.de/">Christoph Lassner</a>,
                <a href="https://vsitzmann.github.io/">Vincent Sitzmann</a>,
                <a href="http://ricardomartinbrualla.com/">Ricardo Martin-Brualla</a>,
                <a href="https://stephenlombardi.github.io/">Stephen Lombardi</a>,
                <a href="http://www.cs.cmu.edu/~tsimon/">Tomas Simon</a>,
                <a href="https://www.mpi-inf.mpg.de/departments/visual-computing-and-artificial-intelligence">Christian Theobalt</a>,
                <a href="https://www.niessnerlab.org/">Matthias Niessner</a>,
                <strong>Jonathan T. Barron</strong>,
                <a href="https://stanford.edu/~gordonwz/">Gordon Wetzstein</a>,
                <a href="https://zollhoefer.com/">Michael Zollhoefer</a>,
                <a href="https://people.mpi-inf.mpg.de/~golyanik/">Vladislav Golyanik</a>
                <br>
                <em>Arxiv</em>, 2021
                <br>
                <p></p>
                <p>
                A survey of recent progress in neural rendering.
                </p>
              </td>
            </tr>
            
            <tr onmouseout="npil_stop()" onmouseover="npil_start()">
              <td style="padding:20px;width:25%;vertical-align:middle">
                <div class="one">
                  <div class="two" id='npil_image'>
                    <img src='images/npil_after.jpg' width="160"></div>
                  <img src='images/npil_before.jpg' width="160">
                </div>
                <script type="text/javascript">
                  function npil_start() {
                    document.getElementById('npil_image').style.opacity = "1";
                  }

                  function npil_stop() {
                    document.getElementById('npil_image').style.opacity = "0";
                  }
                  npil_stop()
                </script>
              </td>
              <td style="padding:20px;width:75%;vertical-align:middle">
                <a href="https://markboss.me/publication/2021-neural-pil/">
                  <span class="papertitle">Neural-PIL: Neural Pre-Integrated Lighting for Reflectance Decomposition</span>
                </a>
                <br>

                <a href="https://markboss.me">Mark Boss</a>, 
                <a href="https://varunjampani.github.io">Varun Jampani</a>,
                <a href="https://uni-tuebingen.de/en/fakultaeten/mathematisch-naturwissenschaftliche-fakultaet/fachbereiche/informatik/lehrstuehle/computergrafik/lehrstuhl/mitarbeiter/raphael-braun/">Raphael Braun</a>, <br>
                <a href="http://people.csail.mit.edu/celiu/">Ce Liu</a>,
                <strong>Jonathan T. Barron</strong>,
                <a href="https://uni-tuebingen.de/en/faculties/faculty-of-science/departments/computer-science/lehrstuehle/computergrafik/computer-graphics/staff/prof-dr-ing-hendrik-lensch/">Hendrik P. A. Lensch</a>
                <br>
                <em>NeurIPS</em>, 2021
                <br>
                <a href="https://markboss.me/publication/2021-neural-pil/">project page</a> /
                <a href="https://www.youtube.com/watch?v=p5cKaNwVp4M">video</a> /
                <a href="https://arxiv.org/abs/2110.14373">arXiv</a>
                <p></p>
                <p>
                Replacing a costly illumination integral with a simple network query enables more accurate novel view-synthesis and relighting compared to NeRD.
                </p>
              </td>
            </tr>
            
            
            <tr onmouseout="hypernerf_stop()" onmouseover="hypernerf_start()">
              <td style="padding:20px;width:25%;vertical-align:middle">
                <div class="one">
                  <div class="two" id='hypernerf_image'><video  width=100% height=100% muted autoplay loop>
                  <source src="images/hypernerf_after.mp4" type="video/mp4">
                  Your browser does not support the video tag.
                  </video></div>
                  <img src='images/hypernerf_before.jpg' width="160">
                </div>
                <script type="text/javascript">
                  function hypernerf_start() {
                    document.getElementById('hypernerf_image').style.opacity = "1";
                  }

                  function hypernerf_stop() {
                    document.getElementById('hypernerf_image').style.opacity = "0";
                  }
                  hypernerf_stop()
                </script>
              </td>
              <td style="padding:20px;width:75%;vertical-align:middle">
                <a href="https://hypernerf.github.io/">
                  <span class="papertitle">HyperNeRF: A Higher-Dimensional Representation
for Topologically Varying Neural Radiance Fields</span>
                </a>
                <br>
                <a href="https://keunhong.com">Keunhong Park</a>,
                <a href="https://utkarshsinha.com">Utkarsh Sinha</a>, 
                <a href="https://phogzone.com/">Peter Hedman</a>,
                <strong>Jonathan T. Barron</strong>, <br>
                <a href="http://sofienbouaziz.com">Sofien Bouaziz</a>,
                <a href="https://www.danbgoldman.com">Dan B Goldman</a>,
                <a href="http://www.ricardomartinbrualla.com">Ricardo Martin-Brualla</a>, 
                <a href="https://homes.cs.washington.edu/~seitz/">Steven M. Seitz</a>
                <br>
                <em>SIGGRAPH Asia</em>, 2021 
                <br>
                <a href="https://hypernerf.github.io/">project page</a>
                /
                <a href="https://arxiv.org/abs/2106.13228">arXiv</a>
                <p></p>
                <p>Applying ideas from level set methods to NeRF lets you represent scenes that deform and change shape.</p>
              </td>
            </tr> 

            <tr onmouseout="nerfactor_stop()" onmouseover="nerfactor_start()">
              <td style="padding:20px;width:25%;vertical-align:middle">
                <div class="one">
                  <div class="two" id='nerfactor_image'>
                    <img src='images/nerfactor_after.png' width="160"></div>
                  <img src='images/nerfactor_before.png' width="160">
                </div>
                <script type="text/javascript">
                  function nerfactor_start() {
                    document.getElementById('nerfactor_image').style.opacity = "1";
                  }

                  function nerfactor_stop() {
                    document.getElementById('nerfactor_image').style.opacity = "0";
                  }
                  nerfactor_stop()
                </script>
              </td>
              <td style="padding:20px;width:75%;vertical-align:middle">
                <a href="https://people.csail.mit.edu/xiuming/projects/nerfactor/">
                <span class="papertitle">NeRFactor: Neural Factorization of Shape and Reflectance<br>
  Under an Unknown Illumination</span>
                </a>
                <br>
                <a href="https://people.csail.mit.edu/xiuming/">Xiuming Zhang</a>,
                <a href="https://pratulsrinivasan.github.io/">Pratul Srinivasan</a>,
                <a href="https://boyangdeng.com/">Boyang Deng</a>,<br>
                <a href="https://www.pauldebevec.com/">Paul Debevec</a>,
                <a href="http://billf.mit.edu/">William T. Freeman</a>,
                <strong>Jonathan T. Barron</strong>
                <br>
                <em>SIGGRAPH Asia</em>, 2021 
                <br>
                <a href="https://people.csail.mit.edu/xiuming/projects/nerfactor/">project page</a>
                /
                <a href="https://arxiv.org/abs/2106.01970">arXiv</a>
                /
                <a href="https://www.youtube.com/watch?v=UUVSPJlwhPg">video</a>
                <p></p>
                <p>By placing priors on illumination and materials, we can recover NeRF-like models of the intrinsics of a scene from a single multi-image capture.</p>
              </td>
              
            <tr onmouseout="dualfont_stop()" onmouseover="dualfont_start()">
              <td style="padding:20px;width:25%;vertical-align:middle">
                <div class="one">
                  <div class="two" id='dualfont_image'><img src='images/dualfont_after.png'></div>
                  <img src='images/dualfont_before.png'>
                </div>
                <script type="text/javascript">
                  function dualfont_start() {
                    document.getElementById('dualfont_image').style.opacity = "1";
                  }

                  function dualfont_stop() {
                    document.getElementById('dualfont_image').style.opacity = "0";
                  }
                  dualfont_stop()
                </script>
              </td>
              <td style="padding:20px;width:75%;vertical-align:middle">
                <a href="https://arxiv.org/abs/2109.06627">
                  <span class="papertitle">Scalable Font Reconstruction with Dual Latent Manifolds</span>
                </a>
                <br>
                <a href="http://www.cs.cmu.edu/~asrivats/">Nikita Srivatsan</a>,
                <a href="http://siwu.io/">Si Wu</a>,
                <strong>Jonathan T. Barron</strong>,
                <a href="http://cseweb.ucsd.edu/~tberg/">Taylor Berg-Kirkpatrick</a>
                <br>
                <em>EMNLP</em>, 2021
                <br>
                <p></p>
                <p>VAEs can be used to disentangle a font's style from its content, and to generalize to characters that were never observed during training.</p>
              </td>
            </tr>
            
            <tr onmouseout="mipnerf_stop()" onmouseover="mipnerf_start()"  bgcolor="#ffffd0">
              <td style="padding:20px;width:25%;vertical-align:middle">
                <div class="one">
                  <div class="two" id='mipnerf_image'><video  width=100% height=100% muted autoplay loop>
                  <source src="images/mipnerf_ipe_yellow.mp4" type="video/mp4">
                  Your browser does not support the video tag.
                  </video></div>
                  <img src='images/mipnerf_ipe_yellow.png' width="160">
                </div>
                <script type="text/javascript">
                  function mipnerf_start() {
                    document.getElementById('mipnerf_image').style.opacity = "1";
                  }

                  function mipnerf_stop() {
                    document.getElementById('mipnerf_image').style.opacity = "0";
                  }
                  mipnerf_stop()
                </script>
              </td>
              <td style="padding:20px;width:75%;vertical-align:middle">
                <a href="http://jonbarron.info/mipnerf">
                  <span class="papertitle">Mip-NeRF: A Multiscale Representation for Anti-Aliasing Neural Radiance Fields</span>
                </a>
                <br>
                <strong>Jonathan T. Barron</strong>,
                <a href="https://bmild.github.io/">Ben Mildenhall</a>,
                <a href="http://matthewtancik.com/">Matthew Tancik</a>, <br>
                <a href="https://phogzone.com/">Peter Hedman</a>,
                <a href="http://www.ricardomartinbrualla.com/">Ricardo Martin-Brualla</a>,
                <a href="https://pratulsrinivasan.github.io/">Pratul Srinivasan</a>
                <br>
                <em>ICCV</em>, 2021 &nbsp <font color="red"><strong>(Oral Presentation, Best Paper Honorable Mention)</strong></font>
                <br>
                <a href="http://jonbarron.info/mipnerf">project page</a>
                /
                <a href="https://arxiv.org/abs/2103.13415">arXiv</a>
                /
                <a href="https://youtu.be/EpH175PY1A0">video</a>
                /
                <a href="https://github.com/google/mipnerf">code</a>
                <p></p>
                <p>NeRF is aliased, but we can anti-alias it by casting cones and prefiltering the positional encoding function.</p>
              </td>
            </tr> 

            <tr onmouseout="nerfbake_stop()" onmouseover="nerfbake_start()">
              <td style="padding:20px;width:25%;vertical-align:middle">
                <div class="one">
                  <div class="two" id='nerfbake_image'><video  width=100% height=100% muted autoplay loop>
                  <source src="images/nerfbake_15.mp4" type="video/mp4">
                  Your browser does not support the video tag.
                  </video></div>
                  <img src='images/nerfbake_160.png' width="160">
                </div>
                <script type="text/javascript">
                  function nerfbake_start() {
                    document.getElementById('nerfbake_image').style.opacity = "1";
                  }

                  function nerfbake_stop() {
                    document.getElementById('nerfbake_image').style.opacity = "0";
                  }
                  nerfbake_stop()
                </script>
              </td>
              <td style="padding:20px;width:75%;vertical-align:middle">
                <a href="http://nerf.live">
                <span class="papertitle">Baking Neural Radiance Fields for Real-Time View Synthesis</span>
                </a>
                <br>
                <a href="https://phogzone.com/">Peter Hedman</a>,
                <a href="https://pratulsrinivasan.github.io/">Pratul Srinivasan</a>,
                <a href="https://bmild.github.io/">Ben Mildenhall</a>,
                <strong>Jonathan T. Barron</strong>,
                <a href="https://www.pauldebevec.com/">Paul Debevec</a>
                <br>
                <em>ICCV</em>, 2021 &nbsp <font color="red"><strong>(Oral Presentation)</strong></font>
                <br>
                <a href="http://nerf.live">project page</a>
                /
                <a href="https://arxiv.org/abs/2103.14645">arXiv</a>
                /
                <a href="https://www.youtube.com/watch?v=5jKry8n5YO8">video</a>
                /
                <a href="https://nerf.live/#demos">demo</a>
                <p></p>
                <p>Baking a trained NeRF into a sparse voxel grid of colors and features lets you render it in real-time in your browser.</p>
              </td>



            <tr onmouseout="nerfie_stop()" onmouseover="nerfie_start()">
              <td style="padding:20px;width:25%;vertical-align:middle">
                <div class="one">
                  <div class="two" id='nerfie_image'><video  width=100% height=100% muted autoplay loop>
                  <source src="images/nerfie_after.mp4" type="video/mp4">
                  Your browser does not support the video tag.
                  </video></div>
                  <img src='images/nerfie_before.jpg' width="160">
                </div>
                <script type="text/javascript">
                  function nerfie_start() {
                    document.getElementById('nerfie_image').style.opacity = "1";
                  }
                  function nerfie_stop() {
                    document.getElementById('nerfie_image').style.opacity = "0";
                  }
                  nerfie_stop()
                </script>
              </td>
              <td style="padding:20px;width:75%;vertical-align:middle">
                <a href="https://nerfies.github.io/">
                  <span class="papertitle">Nerfies: Deformable Neural Radiance Fields</span>
                </a>
                <br>
                
                <a href="https://keunhong.com">Keunhong Park</a>,
                <a href="https://utkarshsinha.com">Utkarsh Sinha</a>,
                <strong>Jonathan T. Barron</strong>, <br>
                <a href="http://sofienbouaziz.com">Sofien Bouaziz</a>,
                <a href="https://www.danbgoldman.com">Dan B Goldman</a>,
                <a href="https://homes.cs.washington.edu/~seitz/">Steven M. Seitz</a>,
                <a href="http://www.ricardomartinbrualla.com">Ricardo-Martin Brualla</a>
                <br>
                <em>ICCV</em>, 2021 &nbsp <font color="red"><strong>(Oral Presentation)</strong></font>
                <br>
                <a href="https://nerfies.github.io/">project page</a> /
                <a href="https://arxiv.org/abs/2011.12948">arXiv</a> /
                <a href="https://www.youtube.com/watch?v=MrKrnHhk8IA">video</a>
                <p></p>
                <p>Building deformation fields into NeRF lets you capture non-rigid subjects, like people.
                </p>
              </td>
            </tr> 


            <tr onmouseout="c5_stop()" onmouseover="c5_start()">
              <td style="padding:20px;width:25%;vertical-align:middle">
                <div class="one">
                  <div class="two" id='c5_image'>
                    <img src='images/c5_after.jpg' width="160"></div>
                  <img src='images/c5_before.jpg' width="160">
                </div>
                <script type="text/javascript">
                  function c5_start() {
                    document.getElementById('c5_image').style.opacity = "1";
                  }

                  function c5_stop() {
                    document.getElementById('c5_image').style.opacity = "0";
                  }
                  c5_stop()
                </script>
              </td>
              <td style="padding:20px;width:75%;vertical-align:middle">
                <a href="https://arxiv.org/abs/2011.11890">
                  <span class="papertitle">Cross-Camera Convolutional Color Constancy</span>
                </a>
                <br>
                <a href="https://sites.google.com/corp/view/mafifi">Mahmoud Afifi</a>,
                <strong>Jonathan T. Barron</strong>,
                <a href="http://www.chloelegendre.com/">Chloe LeGendre</a>,
                <a href="https://research.google/people/105312/">Yun-Ta Tsai</a>,
                <a href="https://www.linkedin.com/in/fbleibel/">Francois Bleibel</a>
                <br>
                <em>ICCV</em>, 2021 &nbsp <font color="red"><strong>(Oral Presentation)</strong></font>
                <br>
                <p></p>
                <p>
                  With some extra (unlabeled) test-set images, you can build a hypernetwork that calibrates itself at test time to previously-unseen cameras.
                </p>
              </td>
            </tr> 


            <tr onmouseout="dualdefocus_stop()" onmouseover="dualdefocus_start()">
              <td style="padding:20px;width:25%;vertical-align:middle">
                <div class="one">
                  <div class="two" id='dualdefocus_image'>
                    <img src='images/dualdefocus_after.jpg' width="160"></div>
                  <img src='images/dualdefocus_before.jpg' width="160">
                </div>
                <script type="text/javascript">
                  function dualdefocus_start() {
                    document.getElementById('dualdefocus_image').style.opacity = "1";
                  }

                  function dualdefocus_stop() {
                    document.getElementById('dualdefocus_image').style.opacity = "0";
                  }
                  dualdefocus_stop()
                </script>
              </td>
              <td style="padding:20px;width:75%;vertical-align:middle">
                <a href="https://imaging.cs.cmu.edu/dual_pixels/">
                  <span class="papertitle">Defocus Map Estimation and Deblurring from a Single Dual-Pixel Image</span>
                </a>
                <br>
                <a href="https://shumianxin.github.io/">Shumian Xin</a>,
                <a href="http://nealwadhwa.com">Neal Wadhwa</a>,
                <a href="https://tianfan.info/">Tianfan Xue</a>,
                <strong>Jonathan T. Barron</strong>, <br>
                <a href="https://pratulsrinivasan.github.io/">Pratul Srinivasan</a>,
                <a href="http://people.csail.mit.edu/jiawen/">Jiawen Chen</a>,
                <a href="https://www.cs.cmu.edu/~igkioule/">Ioannis Gkioulekas</a>,
                <a href="http://rahuldotgarg.appspot.com/">Rahul Garg</a>
                <br>
                <em>ICCV</em>, 2021 &nbsp <font color="red"><strong>(Oral Presentation)</strong></font>
                <br>
                <a href="https://imaging.cs.cmu.edu/dual_pixels/">project page</a> /
                <a href="https://github.com/cmu-ci-lab/dual_pixel_defocus_estimation_deblurring">code</a>
                <br>
                <p></p>
                <p>
                  Multiplane images can be used to simultaneously deblur dual-pixel images, despite variable defocus due to depth variation in the scene.
                </p>
              </td>
            </tr> 


            <tr onmouseout="nerd_stop()" onmouseover="nerd_start()">
              <td style="padding:20px;width:25%;vertical-align:middle">
                <div class="one">
                  <div class="two" id='nerd_image'><video  width=100% height=100% muted autoplay loop>
                  <source src="images/nerd_160.mp4" type="video/mp4">
                  Your browser does not support the video tag.
                  </video></div>
                  <img src='images/nerd_160.jpg' width="160">
                </div>
                <script type="text/javascript">
                  function nerd_start() {
                    document.getElementById('nerd_image').style.opacity = "1";
                  }

                  function nerd_stop() {
                    document.getElementById('nerd_image').style.opacity = "0";
                  }
                  nerd_stop()
                </script>
              </td>
              <td style="padding:20px;width:75%;vertical-align:middle">
                <a href="https://markboss.me/publication/2021-nerd/">
                  <span class="papertitle">NeRD: Neural Reflectance Decomposition from Image Collections</span>
                </a>
                <br>

                <a href="https://markboss.me">Mark Boss</a>, 
                <a href="https://uni-tuebingen.de/en/fakultaeten/mathematisch-naturwissenschaftliche-fakultaet/fachbereiche/informatik/lehrstuehle/computergrafik/lehrstuhl/mitarbeiter/raphael-braun/">Raphael Braun</a>,
                <a href="https://varunjampani.github.io">Varun Jampani</a>,
                <strong>Jonathan T. Barron</strong>,
                <a href="http://people.csail.mit.edu/celiu/">Ce Liu</a>,
                <a href="https://uni-tuebingen.de/en/faculties/faculty-of-science/departments/computer-science/lehrstuehle/computergrafik/computer-graphics/staff/prof-dr-ing-hendrik-lensch/">Hendrik P. A. Lensch</a>
                <br>
                <em>ICCV</em>, 2021
                <br>
                <a href="https://markboss.me/publication/2021-nerd/">project page</a> /
                <a href="https://www.youtube.com/watch?v=JL-qMTXw9VU">video</a> /
                <a href="https://github.com/cgtuebingen/NeRD-Neural-Reflectance-Decomposition">code</a> /
                <a href="https://arxiv.org/abs/2012.03918">arXiv</a>
                <p></p>
                <p>
                A NeRF-like model that can decompose (and mesh) objects with non-Lambertian reflectances, complex geometry, and unknown illumination.
                </p>
              </td>
            </tr>

            <tr onmouseout="flare_stop()" onmouseover="flare_start()">
              <td style="padding:20px;width:25%;vertical-align:middle">
                <div class="one">
                  <div class="two" id='flare_image'>
                    <img src='images/flare_after.jpg' width="160"></div>
                  <img src='images/flare_before.jpg' width="160">
                </div>
                <script type="text/javascript">
                  function flare_start() {
                    document.getElementById('flare_image').style.opacity = "1";
                  }

                  function flare_stop() {
                    document.getElementById('flare_image').style.opacity = "0";
                  }
                  flare_stop()
                </script>
              </td>
              <td style="padding:20px;width:75%;vertical-align:middle">
                <a href="https://arxiv.org/abs/2011.12485">
                  <span class="papertitle">How to Train Neural Networks for Flare Removal</span>
                </a>
                <br>
                <a href="http://yicheng.rice.edu/">Yicheng Wu</a>,
                <a href="https://scholar.google.com/citations?user=BxqV_RsAAAAJ">Qiurui He</a>,
                <a href="https://tianfan.info/">Tianfan Xue</a>,
                <a href="http://rahuldotgarg.appspot.com/">Rahul Garg</a>, <br>
                <a href="http://people.csail.mit.edu/jiawen/">Jiawen Chen</a>,
                <a href="https://computationalimaging.rice.edu/team/ashok-veeraraghavan/">Ashok Veeraraghavan</a>,
                <strong>Jonathan T. Barron</strong>
                <br>
                <em>ICCV</em>, 2021
                <br>
                <a href="https://yichengwu.github.io/flare-removal/">project page</a>  / 
                <a href="https://arxiv.org/abs/2011.12485">arXiv</a> 
                <p></p>
                <p>
                  Simulating the optics of a camera's lens lets you train a model that removes lens flare from a single image.
                </p>
              </td>
            </tr> 


            <tr onmouseout="inerf_stop()" onmouseover="inerf_start()">
              <td style="padding:20px;width:25%;vertical-align:middle">
                <div class="one">
                  <div class="two" id='inerf_image'><video  width=100% height=100% muted autoplay loop>
                  <source src="images/inerf_after.mp4" type="video/mp4">
                  Your browser does not support the video tag.
                  </video></div>
                  <img src='images/inerf_before.jpg' width="160">
                </div>
                <script type="text/javascript">
                  function inerf_start() {
                    document.getElementById('inerf_image').style.opacity = "1";
                  }
                  function inerf_stop() {
                    document.getElementById('inerf_image').style.opacity = "0";
                  }
                  inerf_stop()
                </script>
              </td>
              <td style="padding:20px;width:75%;vertical-align:middle">
                <a href="http://yenchenlin.me/inerf/">
                  <span class="papertitle">iNeRF: Inverting Neural Radiance Fields for Pose Estimation</span>
                </a>
                <br>
                <a href="https://yenchenlin.me/">Lin Yen-Chen</a>, 
                <a href="http://www.peteflorence.com/">Pete Florence</a>, 
                <strong>Jonathan T. Barron</strong>,  <br>
                <a href="https://meche.mit.edu/people/faculty/ALBERTOR@MIT.EDU">Alberto Rodriguez</a>,
                <a href="http://web.mit.edu/phillipi/">Phillip Isola</a>,
                <a href="https://scholar.google.com/citations?user=_BPdgV0AAAAJ&hl=en">Tsung-Yi Lin</a>
                <br>
                <em>IROS</em>, 2021  
                <br>
                <a href="http://yenchenlin.me/inerf/">project page</a> /
                <a href="https://arxiv.org/abs/2012.05877">arXiv</a> /
                <a href="https://www.youtube.com/watch?v=eQuCZaQN0tI">video</a>
                <p></p>
                <p>Given an image of an object and a NeRF of that object, you can estimate that object's pose.
                </p>
              </td>
            </tr> 

            <tr onmouseout="ibrnet_stop()" onmouseover="ibrnet_start()">
              <td style="padding:20px;width:25%;vertical-align:middle">
                <div class="one">
                  <div class="two" id='ibrnet_image'><video  width=100% height=100% muted autoplay loop>
                  <source src="images/ibrnet_after.mp4" type="video/mp4">
                  Your browser does not support the video tag.
                  </video></div>
                  <img src='images/ibrnet_before.jpg' width="160">
                </div>
                <script type="text/javascript">
                  function ibrnet_start() {
                    document.getElementById('ibrnet_image').style.opacity = "1";
                  }

                  function ibrnet_stop() {
                    document.getElementById('ibrnet_image').style.opacity = "0";
                  }
                  ibrnet_stop()
                </script>
              </td>
              <td style="padding:20px;width:75%;vertical-align:middle">
                <a href="https://ibrnet.github.io/">
                  <span class="papertitle">IBRNet: Learning Multi-View Image-Based Rendering</span>
                </a>
                <br>
                <a href="https://www.cs.cornell.edu/~qqw/">Qianqian Wang</a>,
                <a href="https://www.linkedin.com/in/zhicheng-wang-96116897/">Zhicheng Wang</a>,
                <a href="https://www.kylegenova.com/">Kyle Genova</a>,
                <a href="https://pratulsrinivasan.github.io/">Pratul Srinivasan</a>,
                <a href="https://scholar.google.com/citations?user=Rh9T3EcAAAAJ&hl=en">Howard Zhou</a>, <br>
                <strong>Jonathan T. Barron</strong>, 
                <a href="http://www.ricardomartinbrualla.com/">Ricardo Martin-Brualla</a>,
                <a href="https://www.cs.cornell.edu/~snavely/">Noah Snavely</a>, 
                <a href="https://www.cs.princeton.edu/~funk/">Thomas Funkhouser</a>
                <br>
                <em>CVPR</em>, 2021
                <br>
                <a href="https://ibrnet.github.io/">project page</a> /
                <a href="https://github.com/googleinterns/IBRNet">code</a> / 
                <a href="https://arxiv.org/abs/2102.13090">arXiv</a>
                <p></p>
                <p>By learning how to pay attention to input images at render time, 
                    we can amortize inference for view synthesis and reduce error rates by 15%.</p>
              </td>
            </tr>

            <tr onmouseout="nerv_stop()" onmouseover="nerv_start()">
              <td style="padding:20px;width:25%;vertical-align:middle">
                <div class="one">
                  <div class="two" id='nerv_image'><video  width=100% height=100% muted autoplay loop>
                  <source src="images/hotdog.mp4" type="video/mp4">
                  Your browser does not support the video tag.
                  </video></div>
                  <img src='images/hotdog.jpg' width="160">
                </div>
                <script type="text/javascript">
                  function nerv_start() {
                    document.getElementById('nerv_image').style.opacity = "1";
                  }

                  function nerv_stop() {
                    document.getElementById('nerv_image').style.opacity = "0";
                  }
                  nerv_stop()
                </script>
              </td>
              <td style="padding:20px;width:75%;vertical-align:middle">
                <a href="https://pratulsrinivasan.github.io/nerv/">
                  <span class="papertitle">NeRV: Neural Reflection and Visibility Fields for Relighting and View Synthesis</span>
                </a>
                <br>
                <a href="https://pratulsrinivasan.github.io/">Pratul Srinivasan</a>,
                <a href="https://boyangdeng.com/">Boyang Deng</a>,
                <a href="https://people.csail.mit.edu/xiuming/">Xiuming Zhang</a>, <br>
                <a href="http://matthewtancik.com/">Matthew Tancik</a>,
                <a href="https://bmild.github.io/">Ben Mildenhall</a>,
                <strong>Jonathan T. Barron</strong>
                <br>
                <em>CVPR</em>, 2021
                <br>
                <a href="https://pratulsrinivasan.github.io/nerv/">project page</a> /
                <a href="https://www.youtube.com/watch?v=4XyDdvhhjVo">video</a> /
                <a href="https://arxiv.org/abs/2012.03927">arXiv</a>
                <p></p>
                <p>Using neural approximations of expensive visibility integrals lets you recover relightable NeRF-like models.</p>
              </td>
            </tr>


            <tr onmouseout="winr_stop()" onmouseover="winr_start()">
              <td style="padding:20px;width:25%;vertical-align:middle">
                <div class="one">
                  <div class="two" id='winr_image'><video  width=100% height=100% muted autoplay loop>
                  <source src="images/notre_160.mp4" type="video/mp4">
                  Your browser does not support the video tag.
                  </video></div>
                  <img src='images/notre.jpg' width="160">
                </div>
                <script type="text/javascript">
                  function winr_start() {
                    document.getElementById('winr_image').style.opacity = "1";
                  }
                  function winr_stop() {
                    document.getElementById('winr_image').style.opacity = "0";
                  }
                  winr_stop()
                </script>
              </td>
              <td style="padding:20px;width:75%;vertical-align:middle">
                <a href="http://www.matthewtancik.com/learnit">
                  <span class="papertitle">Learned Initializations for Optimizing Coordinate-Based Neural Representations</span>
                </a>
                <br>
                <a href="http://matthewtancik.com/">Matthew Tancik*</a>,
                <a href="https://bmild.github.io/">Ben Mildenhall*</a>,
                <a href="https://www.linkedin.com/in/terrance-wang/">Terrance Wang</a>,
                <a href="https://www.linkedin.com/in/divi-schmidt-262044180/">Divi Schmidt</a>, <br>
                <a href="https://pratulsrinivasan.github.io/">Pratul Srinivasan</a>,
                <strong>Jonathan T. Barron</strong>,
                <a href="https://www2.eecs.berkeley.edu/Faculty/Homepages/yirenng.html">Ren Ng</a>
                <br>
                <em>CVPR</em>, 2021 &nbsp <font color="red"><strong>(Oral Presentation)</strong></font>
                <br>
                <a href="http://www.matthewtancik.com/learnit">project page</a> /
                <a href="https://www.youtube.com/watch?v=A-r9itCzcyo">video</a> /
                <a href="https://arxiv.org/abs/2012.02189">arXiv</a> 
                <p></p>
                <p>Using meta-learning to find weight initializations for coordinate-based MLPs allows them to converge faster and generalize better.</p>
              </td>
            </tr>

            <tr onmouseout="nerfw_stop()" onmouseover="nerfw_start()">
              <td style="padding:20px;width:25%;vertical-align:middle">
                <div class="one">
                  <div class="two" id='nerfw_image'><video  width=100% height=100% muted autoplay loop>
                  <source src="images/nerfw_after.mp4" type="video/mp4">
                  Your browser does not support the video tag.
                  </video></div>
                  <img src='images/nerfw_before.jpg' width="160">
                </div>
                <script type="text/javascript">
                  function nerfw_start() {
                    document.getElementById('nerfw_image').style.opacity = "1";
                  }

                  function nerfw_stop() {
                    document.getElementById('nerfw_image').style.opacity = "0";
                  }
                  nerfw_stop()
                </script>
              </td>
              <td style="padding:20px;width:75%;vertical-align:middle">
                <a href="https://nerf-w.github.io/">
                  <span class="papertitle">NeRF in the Wild: Neural Radiance Fields for Unconstrained Photo Collections</span>
                </a>
                <br>
                <a href="http://www.ricardomartinbrualla.com/">Ricardo Martin-Brualla*</a>,
                <a href="https://scholar.google.com/citations?user=g98QcZUAAAAJ&hl=en">Noha Radwan*</a>,
                <a href="https://research.google/people/105804/">Mehdi S. M. Sajjadi*</a>, <br>
                <strong>Jonathan T. Barron</strong>,
                <a href="https://scholar.google.com/citations?user=FXNJRDoAAAAJ&hl=en">Alexey Dosovitskiy</a>,
                <a href="http://www.stronglyconvex.com/about.html">Daniel Duckworth</a>
                <br>
                <em>CVPR</em>, 2021 &nbsp <font color="red"><strong>(Oral Presentation)</strong></font>
                <br>
                <a href="https://nerf-w.github.io/">project page</a> /
                <a href="https://arxiv.org/abs/2008.02268">arXiv</a> /
                <a href="https://www.youtube.com/watch?v=mRAKVQj5LRA">video</a>
                <p></p>
                <p>Letting NeRF reason about occluders and appearance variation produces photorealistic view synthesis using only unstructured internet photos.</p>
              </td>
            </tr> 

            <tr onmouseout="dualrefl_stop()" onmouseover="dualrefl_start()">
              <td style="padding:20px;width:25%;vertical-align:middle">
                <div class="one">
                  <div class="two" id='dualrefl_image'>
                    <img src='images/dualrefl_after.jpg' width="160"></div>
                  <img src='images/dualrefl_before.jpg' width="160">
                </div>
                <script type="text/javascript">
                  function dualrefl_start() {
                    document.getElementById('dualrefl_image').style.opacity = "1";
                  }

                  function dualrefl_stop() {
                    document.getElementById('dualrefl_image').style.opacity = "0";
                  }
                  dualrefl_stop()
                </script>
              </td>
              <td style="padding:20px;width:75%;vertical-align:middle">
                <a href="http://sniklaus.com/dualref">
                  <span class="papertitle">Learned Dual-View Reflection Removal</span>
                </a>
                <br>
                <a href="http://sniklaus.com/welcome">Simon Niklaus</a>,
                <a href="https://people.eecs.berkeley.edu/~cecilia77/">Xuaner (Cecilia) Zhang</a>,
                <strong>Jonathan T. Barron</strong>, <br>
                <a href="http://nealwadhwa.com">Neal Wadhwa</a>,
                <a href="http://rahuldotgarg.appspot.com/">Rahul Garg</a>,
                <a href="http://web.cecs.pdx.edu/~fliu/">Feng Liu</a>,
                <a href="https://tianfan.info/">Tianfan Xue</a>
                <br>
                <em>WACV</em>, 2021
                <br>
                <a href="http://sniklaus.com/dualref">project page</a> /
                <a href="https://arxiv.org/abs/2010.00702">arXiv</a>
                <p></p>
                <p>
                  Reflections and the things behind them often exhibit parallax, and this lets you remove reflections from stereo pairs.
                </p>
              </td>
            </tr> 


            <tr onmouseout="nlt_stop()" onmouseover="nlt_start()">
              <td style="padding:20px;width:25%;vertical-align:middle">
                <div class="one">
                  <div class="two" id='nlt_image'><video  width=100% height=100% muted autoplay loop>
                  <source src="images/nlt_after.mp4" type="video/mp4">
                  Your browser does not support the video tag.
                  </video></div>
                  <img src='images/nlt_before.jpg' width="160">
                </div>
                <script type="text/javascript">
                  function nlt_start() {
                    document.getElementById('nlt_image').style.opacity = "1";
                  }

                  function nlt_stop() {
                    document.getElementById('nlt_image').style.opacity = "0";
                  }
                  nlt_stop()
                </script>
              </td>
              <td style="padding:20px;width:75%;vertical-align:middle">
                <a href="http://nlt.csail.mit.edu/">
                  <span class="papertitle">Neural Light Transport for Relighting and View Synthesis</span>
                </a>
                <br>
                <a href="http://people.csail.mit.edu/xiuming/">Xiuming Zhang</a>,
                <a href="http://www.seanfanello.it/">Sean Fanello</a>,
                <a href="https://research.google/people/105312/">Yun-Ta Tsai</a>,
                <a href="http://kevinkingo.com/">Tiancheng Sun</a>,
                <a href="https://tianfan.info/">Tianfan Xue</a>,
                <a href="https://research.google/people/106687/">Rohit Pandey</a>,
                <a href="https://www.dtic.ua.es/~sorts/">Sergio Orts-Escolano</a>,
                <a href="https://dl.acm.org/profile/99659224296">Philip Davidson</a>,
                <a href="https://scholar.google.com/citations?user=5D0_pjcAAAAJ&hl=en">Christoph Rhemann</a>,
                <a href="http://www.pauldebevec.com/">Paul Debevec</a>,
                <strong>Jonathan T. Barron</strong>,
                <a href="http://cseweb.ucsd.edu/~ravir/">Ravi Ramamoorthi</a>,
                <a href="http://billf.mit.edu/">William T. Freeman</a>
                <br>
                <em>ACM TOG</em>, 2021
                <br>
                <a href="http://nlt.csail.mit.edu/">project page</a> /
                <a href="https://arxiv.org/abs/2008.03806">arXiv</a> /
                <a href="https://www.youtube.com/watch?v=OGEnCWZihHE">video</a>
                <p></p>
                <p>Embedding a convnet within a predefined texture atlas enables simultaneous view synthesis and relighting.</p>
              </td>
            </tr> 

            <tr onmouseout="lssr_stop()" onmouseover="lssr_start()">
              <td style="padding:20px;width:25%;vertical-align:middle">
                <div class="one">
                  <div class="two" id='lssr_image'>
                    <img src='images/lssr_after.jpg' width="160"></div>
                  <img src='images/lssr_before.jpg' width="160">
                </div>
                <script type="text/javascript">
                  function lssr_start() {
                    document.getElementById('lssr_image').style.opacity = "1";
                  }

                  function lssr_stop() {
                    document.getElementById('lssr_image').style.opacity = "0";
                  }
                  lssr_stop()
                </script>
              </td>
              <td style="padding:20px;width:75%;vertical-align:middle">
                <a href="http://cseweb.ucsd.edu/~viscomp/projects/SIGA20LightstageSuperres/">
                  <span class="papertitle">Light Stage Super-Resolution: Continuous High-Frequency Relighting</span>
                </a>
                <br>
                <a href="http://kevinkingo.com/">Tiancheng Sun</a>,
                <a href="https://cseweb.ucsd.edu/~zex014/">Zexiang Xu</a>
                <a href="http://people.csail.mit.edu/xiuming/">Xiuming Zhang</a>,
                <a href="http://www.seanfanello.it/">Sean Fanello</a>,
                <a href="https://scholar.google.com/citations?user=5D0_pjcAAAAJ&hl=en">Christoph Rhemann</a>, <br>
                <a href="https://www.pauldebevec.com/">Paul Debevec</a>,
                <a href="https://research.google/people/105312/">Yun-Ta Tsai</a>,
                <strong>Jonathan T. Barron</strong>,
                <a href="https://cseweb.ucsd.edu/~ravir/">Ravi Ramamoorthi</a>
                <br>
                <em>SIGGRAPH Asia</em>, 2020  
                <br>
                <a href="http://cseweb.ucsd.edu/~viscomp/projects/SIGA20LightstageSuperres/">project page</a> / 
                <a href="https://arxiv.org/abs/2010.08888">arXiv</a>
                <p></p>
                <p>
                  Scans for light stages are inherently aliased, but we can use learning to super-resolve them.
                </p>
              </td>
            </tr> 


            <tr onmouseout="ff_stop()" onmouseover="ff_start()">
              <td style="padding:20px;width:25%;vertical-align:middle">
                <div class="one">
                  <div class="two" id='ff_image'>
                    <img src='images/lion_ff.jpg' width="160"></div>
                  <img src='images/lion_none.jpg' width="160">
                </div>
                <script type="text/javascript">
                  function ff_start() {
                    document.getElementById('ff_image').style.opacity = "1";
                  }

                  function ff_stop() {
                    document.getElementById('ff_image').style.opacity = "0";
                  }
                  ff_stop()
                </script>
              </td>
              <td style="padding:20px;width:75%;vertical-align:middle">
                <a href="https://bmild.github.io/fourfeat/index.html">
                  <span class="papertitle">Fourier Features Let Networks Learn High Frequency Functions in Low Dimensional Domains</span>
                </a>
                <br>
                <a href="http://matthewtancik.com/">Matthew Tancik*</a>,
                <a href="https://pratulsrinivasan.github.io/">Pratul Srinivasan*</a>,
                <a href="https://bmild.github.io/">Ben Mildenhall*</a>,
                <a href="https://people.eecs.berkeley.edu/~sfk/">Sara Fridovich-Keil</a>, <br>
                <a href="https://www.linkedin.com/in/nithinraghavan">Nithin Raghavan</a>,
                <a href="https://scholar.google.com/citations?user=lvA86MYAAAAJ&hl=en">Utkarsh Singhal</a>,
                <a href="http://cseweb.ucsd.edu/~ravir/">Ravi Ramamoorthi</a>,
                <strong>Jonathan T. Barron</strong>,
                <a href="https://www2.eecs.berkeley.edu/Faculty/Homepages/yirenng.html">Ren Ng</a>
                <br>
                <em>NeurIPS</em>, 2020 &nbsp <font color=#FF8080><strong>(Spotlight)</strong></font>
                <br>
                <a href="https://bmild.github.io/fourfeat/">project page</a> /
                video: <a href="https://www.youtube.com/watch?v=nVA6K6Sn2S4">3 min</a>, <a href="https://www.youtube.com/watch?v=iKyIJ_EtSkw">10 min</a> /
                <a href="https://arxiv.org/abs/2006.10739">arXiv</a> /
                <a href="https://github.com/tancik/fourier-feature-networks">code</a>
                <p></p>
                <p>Composing neural networks with a simple Fourier feature mapping allows them to learn detailed high-frequency functions.</p>
              </td>
            </tr> 

      
            <tr onmouseout="thresh_stop()" onmouseover="thresh_start()">
              <td style="padding:20px;width:25%;vertical-align:middle">
                <div class="one">
                  <div class="two" id='thresh_image'>
                    <img src='images/thresh_after.png' width="160"></div>
                  <img src='images/thresh_before.jpg' width="160">
                </div>
                <script type="text/javascript">
                  function thresh_start() {
                    document.getElementById('thresh_image').style.opacity = "1";
                  }

                  function thresh_stop() {
                    document.getElementById('thresh_image').style.opacity = "0";
                  }
                  thresh_stop()
                </script>
              </td>
              <td style="padding:20px;width:75%;vertical-align:middle">
                <a href="https://arxiv.org/abs/2007.07350">
                  <span class="papertitle">A Generalization of Otsu's Method and Minimum Error Thresholding</span>
                </a>
                <br>
                <strong>Jonathan T. Barron</strong>
                <br>
                <em>ECCV</em>, 2020 &nbsp <font color=#FF8080><strong>(Spotlight)</strong></font>
                <br>
                <a href="https://github.com/jonbarron/hist_thresh">code</a> / 
                <a href="https://www.youtube.com/watch?v=rHtQQlQo1Q4">video</a> / 
                <a href="data/BarronECCV2020.bib">bibtex</a>
                <br>
                <p></p>
                <p>
                A simple and fast Bayesian algorithm that can be written in ~10 lines of code outperforms or matches giant CNNs on image binarization, and unifies three classic thresholding algorithms.
                </p>
              </td>
            </tr>  
      
      
            <tr onmouseout="uflow_stop()" onmouseover="uflow_start()">
              <td style="padding:20px;width:25%;vertical-align:middle">
                <div class="one">
                  <div class="two" id='uflow_image'>
                    <img src='images/uflow_after.png' width="160"></div>
                  <img src='images/uflow_before.jpg' width="160">
                </div>
                <script type="text/javascript">
                  function uflow_start() {
                    document.getElementById('uflow_image').style.opacity = "1";
                  }

                  function uflow_stop() {
                    document.getElementById('uflow_image').style.opacity = "0";
                  }
                  uflow_stop()
                </script>
              </td>
              <td style="padding:20px;width:75%;vertical-align:middle">
                <a href="https://arxiv.org/abs/2006.04902">
                  <span class="papertitle">What Matters in Unsupervised Optical Flow</span>
                </a>
                <br>
                <a href="http://ricojonschkowski.com/">Rico Jonschkowski</a>,
                <a href="https://www.linkedin.com/in/austin-charles-stone-1ba33b138/">Austin Stone</a>,
                <strong>Jonathan T. Barron</strong>, <br>
                <a href="https://research.google/people/ArielGordon/">Ariel Gordon</a>,
                <a href="https://www.linkedin.com/in/kurt-konolige/">Kurt Konolige</a>,
                <a href="https://research.google/people/AneliaAngelova/">Anelia Angelova</a>
                <br>
                <em>ECCV</em>, 2020 &nbsp <font color="red"><strong>(Oral Presentation)</strong></font>
                <br>
                <a href="https://github.com/google-research/google-research/tree/master/uflow">code</a>
                <br>
                <p></p>
                <p>
                Extensive experimentation yields a simple optical flow technique that is trained on only unlabeled videos, but still works as well as supervised techniques.
                </p>
              </td>
            </tr>  
      
            <tr onmouseout="nerf_stop()" onmouseover="nerf_start()"  bgcolor="#ffffd0">
              <td style="padding:20px;width:25%;vertical-align:middle">
                <div class="one">
                  <div class="two" id='nerf_image'><video  width=100% height=100% muted autoplay loop>
                  <source src="images/vase_small.mp4" type="video/mp4">
                  Your browser does not support the video tag.
                  </video></div>
                  <img src='images/vase_still.png' width="160">
                </div>
                <script type="text/javascript">
                  function nerf_start() {
                    document.getElementById('nerf_image').style.opacity = "1";
                  }

                  function nerf_stop() {
                    document.getElementById('nerf_image').style.opacity = "0";
                  }
                  nerf_stop()
                </script>
              </td>
              <td style="padding:20px;width:75%;vertical-align:middle">
                <a href="http://www.matthewtancik.com/nerf">
                  <span class="papertitle">NeRF: Representing Scenes as Neural Radiance Fields for View Synthesis</span>
                </a>
                <br>
                <a href="https://bmild.github.io/">Ben Mildenhall*</a>,
                <a href="https://pratulsrinivasan.github.io/">Pratul Srinivasan*</a>,
                <a href="http://matthewtancik.com/">Matthew Tancik*</a>, <br>
                <strong>Jonathan T. Barron</strong>,
                <a href="http://cseweb.ucsd.edu/~ravir/">Ravi Ramamoorthi</a>,
                <a href="https://www2.eecs.berkeley.edu/Faculty/Homepages/yirenng.html">Ren Ng</a>
                <br>
                <em>ECCV</em>, 2020 &nbsp <font color="red"><strong>(Oral Presentation, Best Paper Honorable Mention, CACM Research Highlight)</strong></font>
                <br>
                <a href="http://www.matthewtancik.com/nerf">project page</a>
                /
                <a href="https://arxiv.org/abs/2003.08934">arXiv</a>
                /
                <a href="https://www.youtube.com/watch?v=LRAqeM8EjOo&t">talk video</a>
                /
                <a href="https://www.youtube.com/watch?v=JuH79E8rdKc">supp video</a>
                /
                <a href="https://github.com/bmild/nerf">code</a>
                /
                <a href="https://cacm.acm.org/magazines/2022/1/257450-nerf/fulltext">CACM</a> <a href="https://cacm.acm.org/magazines/2022/1/257453-technical-perspective-neural-radiance-fields-explode-on-the-scene/fulltext">(foreward)</a>
                <p></p>
                <p>
                Training a tiny non-convolutional neural network to reproduce a scene using volume rendering achieves photorealistic view synthesis.</p>
              </td>
            </tr> 

            <tr onmouseout="porshadmanip_stop()" onmouseover="porshadmanip_start()">
              <td style="padding:20px;width:25%;vertical-align:middle">
                <div class="one">
                  <div class="two" id='porshadmanip_image'>
                    <img src='images/porshadmanip_after.jpg' width="160"></div>
                  <img src='images/porshadmanip_before.jpg' width="160">
                </div>
                <script type="text/javascript">
                  function porshadmanip_start() {
                    document.getElementById('porshadmanip_image').style.opacity = "1";
                  }

                  function porshadmanip_stop() {
                    document.getElementById('porshadmanip_image').style.opacity = "0";
                  }
                  porshadmanip_stop()
                </script>
              </td>
              <td style="padding:20px;width:75%;vertical-align:middle">
                <a href="https://arxiv.org/abs/2005.08925">
                  <span class="papertitle">Portrait Shadow Manipulation</span>
                </a>
                <br>
                <a href="https://people.eecs.berkeley.edu/~cecilia77/">Xuaner (Cecilia) Zhang</a>,
                <strong>Jonathan T. Barron</strong>,
                <a href="https://ai.google/research/people/105312/">Yun-Ta Tsai</a>, <br>
                <a href="https://www.linkedin.com/in/rohit-pandey-bab10b7a/">Rohit Pandey</a>,
                <a href="http://people.csail.mit.edu/xiuming/">Xiuming Zhang</a>,
                <a href="http://graphics.stanford.edu/~renng/">Ren Ng</a>,
                <a href="http://graphics.stanford.edu/~dejacobs/">David E. Jacobs</a>
                <br>
                <em>SIGGRAPH</em>, 2020  
                <br>
                <a href="https://people.eecs.berkeley.edu/~cecilia77/project-pages/portrait">project page</a> / 
                <a href="https://www.youtube.com/watch?v=M_qYTXhzyac">video</a>
                <p></p>
                <p>Networks can be trained to remove shadows cast on human faces and to soften harsh lighting.</p>
              </td>
            </tr>  

            <tr onmouseout="learnaf_stop()" onmouseover="learnaf_start()">
              <td style="padding:20px;width:25%;vertical-align:middle">
                <div class="one">
                  <div class="two" id='learnaf_image'>
                    <img src='images/learnaf_after.jpg' width="160"></div>
                  <img src='images/learnaf_before.jpg' width="160">
                </div>
                <script type="text/javascript">
                  function learnaf_start() {
                    document.getElementById('learnaf_image').style.opacity = "1";
                  }

                  function learnaf_stop() {
                    document.getElementById('learnaf_image').style.opacity = "0";
                  }
                  learnaf_stop()
                </script>
              </td>
              <td style="padding:20px;width:75%;vertical-align:middle">
                <a href="https://arxiv.org/abs/2004.12260">
                  <span class="papertitle">Learning to Autofocus</span>
                </a>
                <br>
                <a href="">Charles Herrmann</a>,
                <a href="">Richard Strong Bowen</a>,
                <a href="http://nealwadhwa.com">Neal Wadhwa</a>, <br>
                <a href="http://rahuldotgarg.appspot.com/">Rahul Garg</a>,
                <a href="https://scholar.google.com/citations?user=BxqV_RsAAAAJ">Qiurui He</a>,
                <strong>Jonathan T. Barron</strong>,
                <a href="http://www.cs.cornell.edu/~rdz/index.htm">Ramin Zabih</a>
                <br>
                <em>CVPR</em>, 2020  
                <br>
                <a href="https://learntoautofocus-google.github.io/">project page</a>
                /
                <a href="https://arxiv.org/abs/2004.12260">arXiv</a>
                <p></p>
                <p>Machine learning can be used to train cameras to autofocus (which is not the same problem as "depth from defocus").</p>
              </td>
            </tr>  

      
            <tr onmouseout="lighthouse_stop()" onmouseover="lighthouse_start()">
              <td style="padding:20px;width:25%;vertical-align:middle">
                <div class="one">
                  <div class="two" id='lh_image'><video width=100% height=100% muted autoplay loop>
                  <source src="images/rings_crop.mp4" type="video/mp4">
                  Your browser does not support the video tag.
                  </video></div>
                  <img src='images/rings.png' width="160">
                </div>
                <script type="text/javascript">
                  function lighthouse_start() {
                    document.getElementById('lh_image').style.opacity = "1";
                  }

                  function lighthouse_stop() {
                    document.getElementById('lh_image').style.opacity = "0";
                  }
                  lighthouse_stop()
                </script>
              </td>
              <td style="padding:20px;width:75%;vertical-align:middle">
                <a href="https://pratulsrinivasan.github.io/lighthouse/">
                  <span class="papertitle">Lighthouse: Predicting Lighting Volumes for Spatially-Coherent Illumination</span>
                </a>
                <br>
                <a href="https://pratulsrinivasan.github.io/">Pratul Srinivasan*</a>,
                <a href="https://bmild.github.io/">Ben Mildenhall*</a>,
                <a href="http://matthewtancik.com/">Matthew Tancik</a>, <br>
                <strong>Jonathan T. Barron</strong>,
                <a href="https://research.google/people/RichardTucker/">Richard Tucker</a>,
                <a href="https://www.cs.cornell.edu/~snavely/">Noah Snavely</a>
                <br>
          <em>CVPR</em>, 2020  
                <br>
                <a href="https://pratulsrinivasan.github.io/lighthouse/">project page</a>
          /
                <a href="https://github.com/pratulsrinivasan/lighthouse">code</a>
          /
                <a href="https://arxiv.org/abs/2003.08367">arXiv</a>
          /
                <a href="https://www.youtube.com/watch?v=KsiZpUFPqIU">video</a>
                <p></p>
                <p>We predict a volume from an input stereo pair that can be used to calculate incident lighting at any 3D point within a scene.</p>
              </td>
            </tr>  

            <tr onmouseout="skyopt_stop()" onmouseover="skyopt_start()">
              <td style="padding:20px;width:25%;vertical-align:middle">
                <div class="one">
                  <div class="two" id='skyopt_image'>
                    <img src='images/skyopt_after.jpg' width="160"></div>
                  <img src='images/skyopt_before.jpg' width="160">
                </div>
                <script type="text/javascript">
                  function skyopt_start() {
                    document.getElementById('skyopt_image').style.opacity = "1";
                  }

                  function skyopt_stop() {
                    document.getElementById('skyopt_image').style.opacity = "0";
                  }
                  skyopt_stop()
                </script>
              </td>
              <td style="padding:20px;width:75%;vertical-align:middle">
                <a href="https://arxiv.org/abs/2006.10172">
                  <span class="papertitle">Sky Optimization: Semantically Aware Image Processing of Skies in Low-Light Photography</span>
                </a>
                <br>
                <a href="https://sites.google.com/corp/view/orly-liba/">Orly Liba</a>,
                <a href="https://www.linkedin.com/in/longqicai/en-us">Longqi Cai</a>,
                <a href="https://ai.google/research/people/105312/">Yun-Ta Tsai</a>,
                <a href="https://research.google/people/EladEban/">Elad Eban</a>,
                <a href="https://research.google/people/YairMovshovitzAttias/">Yair Movshovitz-Attias</a>, <br>
                <a href="https://scholar.google.com/citations?user=2jXxOYQAAAAJ">Yael Pritch</a>,
                <a href="https://www.linkedin.com/in/huizhong-chen-00776432">Huizhong Chen</a>,
                <strong>Jonathan T. Barron</strong>
                <br>
                <em>NTIRE CVPRW</em>, 2020  
                <br>
                <a href="https://google.github.io/sky-optimization/">project page</a>
                <p></p>
                <p>If you want to photograph the sky, it helps to know where the sky is.</p>
              </td>
            </tr>  

            <tr onmouseout="nightsight_stop()" onmouseover="nightsight_start()">
              <td style="padding:20px;width:25%;vertical-align:middle">
                <div class="one">
                  <div class="two" id='nightsight_image'><img src='images/nightsight_after.jpg'></div>
                  <img src='images/nightsight_before.jpg'>
                </div>
                <script type="text/javascript">
                  function nightsight_start() {
                    document.getElementById('nightsight_image').style.opacity = "1";
                  }

                  function nightsight_stop() {
                    document.getElementById('nightsight_image').style.opacity = "0";
                  }
                  nightsight_stop()
                </script>
              </td>
              <td style="padding:20px;width:75%;vertical-align:middle">
                <a href="https://arxiv.org/abs/1910.11336">
                  <span class="papertitle">Handheld Mobile Photography in Very Low Light</span>
                </a>
                <br>
                <a href="https://sites.google.com/site/orlylibaprofessional/">Orly Liba</a>,
                <a href="https://scholar.google.com/citations?user=6PhlPWMAAAAJ">Kiran Murthy</a>,
                <a href="https://ai.google/research/people/105312/">Yun-Ta Tsai</a>,
                <a href="https://www.timothybrooks.com/">Timothy Brooks</a>,
                <a href="https://tianfan.info/">Tianfan Xue</a>,
                <a href="https://scholar.google.com/citations?user=qgc_jY0AAAAJ">Nikhil Karnad</a>,
                <a href="https://scholar.google.com/citations?user=BxqV_RsAAAAJ">Qiurui He</a>,
                <strong>Jonathan T. Barron</strong>,
                <a href="https://ai.google/research/people/105641/">Dillon Sharlet</a>,
                <a href="http://www.geisswerks.com/">Ryan Geiss</a>,
                <a href="https://people.csail.mit.edu/hasinoff/">Samuel W. Hasinoff</a>,
                <a href="https://scholar.google.com/citations?user=2jXxOYQAAAAJ">Yael Pritch</a>,
                <a href="http://graphics.stanford.edu/~levoy/">Marc Levoy</a>
                <br>
                <em>SIGGRAPH Asia</em>, 2019
                <br>
                <a href="https://github.com/google/night-sight/tree/master/docs">project page</a>
                <br>
                <p></p>
                <p>By rethinking metering, white balance, and tone mapping, we can take pictures in places too dark for humans to see clearly.</p>
              </td>
            </tr>

            <tr onmouseout="font_stop()" onmouseover="font_start()">
              <td style="padding:20px;width:25%;vertical-align:middle">
                <div class="one">
                  <div class="two" id='font_image'><img src='images/font_after.png'></div>
                  <img src='images/font_before.png'>
                </div>
                <script type="text/javascript">
                  function font_start() {
                    document.getElementById('font_image').style.opacity = "1";
                  }

                  function font_stop() {
                    document.getElementById('font_image').style.opacity = "0";
                  }
                  font_stop()
                </script>
              </td>
              <td style="padding:20px;width:75%;vertical-align:middle">
                <a href="https://arxiv.org/abs/1910.00748">
                  <span class="papertitle">A Deep Factorization of Style and Structure in Fonts</span>
                </a>
                <br>
                <a href="http://www.cs.cmu.edu/~asrivats/">Nikita Srivatsan</a>,
                <strong>Jonathan T. Barron</strong>,
                <a href="https://people.eecs.berkeley.edu/~klein/">Dan Klein</a>,
                <a href="http://cseweb.ucsd.edu/~tberg/">Taylor Berg-Kirkpatrick</a>
                <br>
                <em>EMNLP</em>, 2019 &nbsp <font color="red"><strong>(Oral Presentation)</strong></font>
                <br>
                <p></p>
                <p>Variational auto-encoders can be used to disentangle a characters style from its content.</p>
              </td>
            </tr>
            
            <tr onmouseout="dpzlearn_stop()" onmouseover="dpzlearn_start()">
              <td style="padding:20px;width:25%;vertical-align:middle">
                <div class="one">
                  <div class="two" id='dpzlearn_image'><img src='images/dpzlearn_after.jpg'></div>
                  <img src='images/dpzlearn_before.jpg'>
                </div>
                <script type="text/javascript">
                  function dpzlearn_start() {
                    document.getElementById('dpzlearn_image').style.opacity = "1";
                  }

                  function dpzlearn_stop() {
                    document.getElementById('dpzlearn_image').style.opacity = "0";
                  }
                  dpzlearn_stop()
                </script>
              </td>
              <td style="padding:20px;width:75%;vertical-align:middle">
                <a href="https://arxiv.org/abs/1904.05822">
                  <span class="papertitle">Learning Single Camera Depth Estimation using Dual-Pixels</span>
                </a>
                <br>
                <a href="http://rahuldotgarg.appspot.com/">Rahul Garg</a>,
                <a href="http://nealwadhwa.com">Neal Wadhwa</a>,
                <a href="">Sameer Ansari</a>,
                <strong>Jonathan T. Barron</strong>
                <br>
                <em>ICCV</em>, 2019 &nbsp <font color="red"><strong>(Oral Presentation)</strong></font>
                <br>
                <a href="https://github.com/google-research/google-research/tree/master/dual_pixels">code</a> /
                <a href="data/GargICCV2019.bib">bibtex</a>
                <p></p>
                <p>Considering the optics of dual-pixel image sensors improves monocular depth estimation techniques.</p>
              </td>
            </tr>
            
            <tr onmouseout="porlight_stop()" onmouseover="porlight_start()">
              <td style="padding:20px;width:25%;vertical-align:middle">
                <div class="one">
                  <div class="two" id='porlight_image'><img src='images/porlight_after.jpg'></div>
                  <img src='images/porlight_before.jpg'>
                </div>
                <script type="text/javascript">
                  function porlight_start() {
                    document.getElementById('porlight_image').style.opacity = "1";
                  }

                  function porlight_stop() {
                    document.getElementById('porlight_image').style.opacity = "0";
                  }
                  porlight_stop()
                </script>
              </td>
              <td style="padding:20px;width:75%;vertical-align:middle">
                <a href="http://cseweb.ucsd.edu/~viscomp/projects/SIG19PortraitRelighting/">
                  <span class="papertitle">Single Image Portrait Relighting</span>
                </a>
                <br>
                <a href="http://kevinkingo.com/">Tiancheng Sun</a>,
                <strong>Jonathan T. Barron</strong>,
                <a href="https://ai.google/research/people/105312/">Yun-Ta Tsai</a>,
                <a href="https://cseweb.ucsd.edu/~zex014/">Zexiang Xu</a>, Xueming Yu,
                <a href="http://ict.usc.edu/profile/graham-fyffe/">Graham Fyffe</a>, Christoph Rhemann, Jay Busch,
                <a href="https://www.pauldebevec.com/">Paul Debevec</a>,
                <a href="https://cseweb.ucsd.edu/~ravir/">Ravi Ramamoorthi</a>
                <br>
                <em>SIGGRAPH</em>, 2019
                <br>
                <a href="http://cseweb.ucsd.edu/~viscomp/projects/SIG19PortraitRelighting/">project page</a> / 
                <a href="https://arxiv.org/abs/1905.00824">arxiv</a> / 
                <a href="https://www.youtube.com/watch?v=yxhGWds_g4I">video</a> /
                <a href="https://petapixel.com/2019/07/16/researchers-developed-an-ai-that-can-relight-portraits-after-the-fact/">press</a> /
                <a href="data/SunSIGGRAPH2019.bib">bibtex</a>
                <br>
                <p></p>
                <p>Training a neural network on light stage scans and environment maps produces an effective relighting method.</p>
              </td>
            </tr>

            <tr onmouseout="loss_stop()" onmouseover="loss_start()" bgcolor="#ffffd0">
              <td style="padding:20px;width:25%;vertical-align:middle">
                <div class="one">
                  <div class="two" id='loss_image'><img src='images/loss_after.png'></div>
                  <img src='images/loss_before.png'>
                </div>
                <script type="text/javascript">
                  function loss_start() {
                    document.getElementById('loss_image').style.opacity = "1";
                  }

                  function loss_stop() {
                    document.getElementById('loss_image').style.opacity = "0";
                  }
                  loss_stop()
                </script>
              </td>
              <td style="padding:20px;width:75%;vertical-align:middle">
                <a href="https://drive.google.com/open?id=1xpZ0fL9h1y9RfcTyPgVkxUrF3VwdkBvq">
                  <span class="papertitle">A General and Adaptive Robust Loss Function</span>
                </a>
                <br>
                <strong>Jonathan T. Barron</strong>
                <br>
                <em>CVPR</em>, 2019 &nbsp <font color="red"><strong>(Oral Presentation, Best Paper Award Finalist)</strong></font>
                <br>
                <a href="https://arxiv.org/abs/1701.03077">arxiv</a> /
                <a href="https://drive.google.com/open?id=1HNveL7xSNh6Ss7sxLK8Mw2L1Fc-rRhL4">supplement</a> /
                <a href="https://youtu.be/BmNKbnF69eY">video</a> /
                <a href="https://www.youtube.com/watch?v=4IInDT_S0ow&t=37m22s">talk</a> / 
                <a href="https://drive.google.com/file/d/1GzRYRIfLHvNLT_QwjHoBjHkBbs3Nbf0x/view?usp=sharing">slides</a> / 
                code: <a href="https://github.com/google-research/google-research/tree/master/robust_loss">TF</a>, <a href="https://github.com/google-research/google-research/tree/master/robust_loss_jax">JAX</a>, <a href="https://github.com/jonbarron/robust_loss_pytorch">pytorch</a> /
                <a href="data/BarronCVPR2019_reviews.txt">reviews</a> /
                <a href="data/BarronCVPR2019.bib">bibtex</a>
                <p></p>
                <p>A single robust loss function is a superset of many other common robust loss functions, and allows training to automatically adapt the robustness of its own loss.</p>
              </td>
            </tr>

            <tr onmouseout="mpi_stop()" onmouseover="mpi_start()">
              <td style="padding:20px;width:25%;vertical-align:middle">
                <div class="one">
                  <div class="two" id='mpi_image'><img src='images/mpi_after.jpg'></div>
                  <img src='images/mpi_before.jpg'>
                </div>
                <script type="text/javascript">
                  function mpi_start() {
                    document.getElementById('mpi_image').style.opacity = "1";
                  }

                  function mpi_stop() {
                    document.getElementById('mpi_image').style.opacity = "0";
                  }
                  mpi_stop()
                </script>
              </td>
              <td style="padding:20px;width:75%;vertical-align:middle">
                <a href="https://drive.google.com/file/d/1TU5L6fnt4Kd49IUOU7aNxor5NIgdHuNG/view?usp=sharing">
                  <span class="papertitle">Pushing the Boundaries of View Extrapolation with Multiplane Images</span>
                </a>
                <br>
                <a href="https://pratulsrinivasan.github.io/">Pratul P. Srinivasan</a>, Richard Tucker,
                <strong>Jonathan T. Barron</strong>,
                <a href="http://cseweb.ucsd.edu/~ravir/">Ravi Ramamoorthi</a>,
                <a href="http://graphics.stanford.edu/~renng/">Ren Ng</a>,
                <a href="https://www.cs.cornell.edu/~snavely/">Noah Snavely</a>
                <br>
                <em>CVPR</em>, 2019 &nbsp <font color="red"><strong>(Oral Presentation, Best Paper Award Finalist)</strong></font>
                <br>
                <a href="https://drive.google.com/file/d/1GUW_n-BAn9Q4VntEA_OTHNJiHO7XfC62/view?usp=sharing">supplement</a> /
                <a href="https://www.youtube.com/watch?v=aJqAaMNL2m4">video</a> /
                <a href="data/SrinivasanCVPR2019.bib">bibtex</a>
                <p></p>
                <p>View extrapolation with multiplane images works better if you reason about disocclusions and disparity sampling frequencies.</p>
              </td>
            </tr>

            <tr onmouseout="unprocessing_stop()" onmouseover="unprocessing_start()">
              <td style="padding:20px;width:25%;vertical-align:middle">
                <div class="one">
                  <div class="two" id='unprocessing_image'><img src='images/unprocessing_after.jpg'></div>
                  <img src='images/unprocessing_before.jpg'>
                </div>
                <script type="text/javascript">
                  function unprocessing_start() {
                    document.getElementById('unprocessing_image').style.opacity = "1";
                  }

                  function unprocessing_stop() {
                    document.getElementById('unprocessing_image').style.opacity = "0";
                  }
                  unprocessing_stop()
                </script>
              </td>
              <td style="padding:20px;width:75%;vertical-align:middle">
                <a href="https://drive.google.com/file/d/1H0Wtd--un2JN76dUJN8iC9fWfkA16n8D/view?usp=sharing">
                  <span class="papertitle">Unprocessing Images for Learned Raw Denoising</span>
                </a>
                <br>
                <a href="http://timothybrooks.com/">Tim Brooks</a>,
                <a href="https://bmild.github.io/">Ben Mildenhall</a>,
                <a href="https://tianfan.info/">Tianfan Xue</a>,
                <a href="http://people.csail.mit.edu/jiawen/">Jiawen Chen</a>,
                <a href="http://www.dsharlet.com/">Dillon Sharlet</a>,
                <strong>Jonathan T. Barron</strong>
                <br>
                <em>CVPR</em>, 2019 &nbsp <font color="red"><strong>(Oral Presentation)</strong></font>
                <br>
                <a href="https://arxiv.org/abs/1811.11127">arxiv</a> /
                <a href="http://timothybrooks.com/tech/unprocessing/">project page</a> /
                <a href="https://github.com/google-research/google-research/tree/master/unprocessing">code</a> / 
                <a href="data/BrooksCVPR2019.bib">bibtex</a>
                <p></p>
                <p>We can learn a better denoising model by processing and unprocessing images the same way a camera does.</p>
              </td>
            </tr>

            <tr onmouseout="motionblur_stop()" onmouseover="motionblur_start()">
              <td style="padding:20px;width:25%;vertical-align:middle">
                <div class="one">
                  <div class="two" id='motionblur_image'><img src='images/motionblur_after.jpg'></div>
                  <img src='images/motionblur_before.jpg'>
                </div>
                <script type="text/javascript">
                  function motionblur_start() {
                    document.getElementById('motionblur_image').style.opacity = "1";
                  }

                  function motionblur_stop() {
                    document.getElementById('motionblur_image').style.opacity = "0";
                  }
                  motionblur_stop()
                </script>
              </td>
              <td style="padding:20px;width:75%;vertical-align:middle">
                <a href="https://drive.google.com/file/d/1hWpA4f6iLVcOkZI3zEAAWKARSQhnVgbY/view?usp=sharing">
                  <span class="papertitle">Learning to Synthesize Motion Blur</span>
                </a>
                <br>
                <a href="http://timothybrooks.com/">Tim Brooks</a>,
                <strong>Jonathan T. Barron</strong>
                <br>
                <em>CVPR</em>, 2019 &nbsp <font color="red"><strong>(Oral Presentation)</strong></font>
                <br>
                <a href="https://arxiv.org/abs/1811.11745">arxiv</a> /
                <a href="https://drive.google.com/file/d/1dUQwBMmQdYYIP0zHR_nDQY-uQbaMdcSN/view?usp=sharing">supplement</a> /
                <a href="http://timothybrooks.com/tech/motion-blur/">project page</a> /
                <a href="https://www.youtube.com/watch?v=8T1jjSz-2V8">video</a> /
                <a href="https://github.com/google-research/google-research/tree/master/motion_blur">code</a> / 
                <a href="data/BrooksBarronCVPR2019.bib">bibtex</a>
                <p></p>
                <p>Frame interpolation techniques can be used to train a network that directly synthesizes linear blur kernels.</p>
              </td>
            </tr>

            <tr onmouseout="darkflash_stop()" onmouseover="darkflash_start()">
              <td style="padding:20px;width:25%;vertical-align:middle">
                <div class="one">
                  <div class="two" id='darkflash_image'><img src='images/darkflash_after.png'></div>
                  <img src='images/darkflash_before.png'>
                </div>
                <script type="text/javascript">
                  function darkflash_start() {
                    document.getElementById('darkflash_image').style.opacity = "1";
                  }

                  function darkflash_stop() {
                    document.getElementById('darkflash_image').style.opacity = "0";
                  }
                  darkflash_stop()
                </script>
              </td>
              <td style="padding:20px;width:75%;vertical-align:middle">
                <a href="https://arxiv.org/abs/1901.01370">
                  <span class="papertitle">Stereoscopic Dark Flash for Low-light Photography</span>
                </a>
                <br>
                <a href="https://www.andrew.cmu.edu/user/jianwan2/">Jian Wang</a>,
                <a href="https://tianfan.info/">Tianfan Xue</a>,
                <strong>Jonathan T. Barron</strong>,
                <a href="http://people.csail.mit.edu/jiawen/">Jiawen Chen</a>
                <br>
                <em>ICCP</em>, 2019
                <br>
                <p></p>
                <p>
                  By making one camera in a stereo pair hyperspectral we can multiplex dark flash pairs in space instead of time.
                </p>
              </td>
            </tr>

            <tr onmouseout="motionstereo_stop()" onmouseover="motionstereo_start()">
              <td style="padding:20px;width:25%;vertical-align:middle">
                <div class="one">
                  <div class="two" id='motionstereo_image'><img src='images/motionstereo_after.png'></div>
                  <img src='images/motionstereo_before.png'>
                </div>
                <script type="text/javascript">
                  function motionstereo_start() {
                    document.getElementById('motionstereo_image').style.opacity = "1";
                  }

                  function motionstereo_stop() {
                    document.getElementById('motionstereo_image').style.opacity = "0";
                  }
                  motionstereo_stop()
                </script>
              </td>
              <td style="padding:20px;width:75%;vertical-align:middle">
                <a href="https://drive.google.com/file/d/1AABFJ3NgD5DAo5JEpEjWZrcQNzjZnvW9/view?usp=sharing">
                  <span class="papertitle">Depth from Motion for Smartphone AR</span>
                </a>
                <br>
                <a href="https://www.linkedin.com/in/valentinjulien/">Julien Valentin</a>,
                <a href="https://www.linkedin.com/in/adarshkowdle/">Adarsh Kowdle</a>,
                <strong>Jonathan T. Barron</strong>, <a href="http://nealwadhwa.com">Neal Wadhwa</a>, and others
                <br>
                <em>SIGGRAPH Asia</em>, 2018
                <br>
                <a href="https://github.com/jonbarron/planar_filter">planar filter toy code</a> / 
                <a href="data/Valentin2018.bib">bibtex</a>
                <p></p>
                <p>Depth cues from camera motion allow for real-time occlusion effects in augmented reality applications.</p>
              </td>
            </tr>

            <tr onmouseout="portrait_stop()" onmouseover="portrait_start()">
              <td style="padding:20px;width:25%;vertical-align:middle">
                <div class="one">
                  <div class="two" id='portrait_image'><img src='images/portrait_after.jpg'></div>
                  <img src='images/portrait_before.jpg'>
                </div>
                <script type="text/javascript">
                  function portrait_start() {
                    document.getElementById('portrait_image').style.opacity = "1";
                  }

                  function portrait_stop() {
                    document.getElementById('portrait_image').style.opacity = "0";
                  }
                  portrait_stop()
                </script>
              </td>
              <td style="padding:20px;width:75%;vertical-align:middle">
                <a href="https://drive.google.com/file/d/13i6DlS9UhGVKmwslLUFnKBwdxFRVQeQj/view?usp=sharing">
                  <span class="papertitle">Synthetic Depth-of-Field with a Single-Camera Mobile Phone</span>
                </a>
                <br>
                <a href="http://nealwadhwa.com">Neal Wadhwa</a>,
                <a href="http://rahuldotgarg.appspot.com/">Rahul Garg</a>,
                <a href="http://graphics.stanford.edu/~dejacobs/">David E. Jacobs</a>, Bryan E. Feldman, Nori Kanazawa, Robert Carroll,
                <a href="http://www.cs.cmu.edu/~ymovshov/">Yair Movshovitz-Attias</a>,
                <strong>Jonathan T. Barron</strong>, Yael Pritch,
                <a href="http://graphics.stanford.edu/~levoy/">Marc Levoy</a>
                <br>
                <em>SIGGRAPH</em>, 2018
                <br>
                <a href="https://arxiv.org/abs/1806.04171">arxiv</a> /
                <a href="https://ai.googleblog.com/2017/10/portrait-mode-on-pixel-2-and-pixel-2-xl.html">blog post</a> /
                <a href="data/Wadhwa2018.bib">bibtex</a>
                <p></p>
                <p>Dual pixel cameras and semantic segmentation algorithms can be used for shallow depth of field effects.</p>
                <p>This system is the basis for "Portrait Mode" on the Google Pixel 2 smartphones</p>
              </td>
            </tr>

            <tr onmouseout="aperture_stop()" onmouseover="aperture_start()">
              <td style="padding:20px;width:25%;vertical-align:middle">
                <div class="one">
                  <div class="two" id='aperture_image'><img src='images/aperture_after.jpg'></div>
                  <img src='images/aperture_before.jpg'>
                </div>
                <script type="text/javascript">
                  function aperture_start() {
                    document.getElementById('aperture_image').style.opacity = "1";
                  }

                  function aperture_stop() {
                    document.getElementById('aperture_image').style.opacity = "0";
                  }
                  aperture_stop()
                </script>
              </td>
              <td style="padding:20px;width:75%;vertical-align:middle">
                <a href="https://drive.google.com/file/d/1MpvxcW7OTJP321QL_q4ZLQ8D653bZZzy/view?usp=sharing">
                  <span class="papertitle">Aperture Supervision for Monocular Depth Estimation</span>
                </a>
                <br>
                <a href="https://pratulsrinivasan.github.io/">Pratul P. Srinivasan</a>,
                <a href="http://rahuldotgarg.appspot.com/">Rahul Garg</a>,
                <a href="http://nealwadhwa.com">Neal Wadhwa</a>,
                <a href="http://graphics.stanford.edu/~renng/">Ren Ng</a>,
                <strong>Jonathan T. Barron</strong>
                <br>
                <em>CVPR</em>, 2018
                <br>
                <a href="https://github.com/google/aperture_supervision">code</a> /
                <a href="data/Srinivasan2018.bib">bibtex</a>
                <p></p>
                <p>Varying a camera's aperture provides a supervisory signal that can teach a neural network to do monocular depth estimation.</p>
              </td>
            </tr>

            <tr onmouseout="deepburst_stop()" onmouseover="deepburst_start()">
              <td style="padding:20px;width:25%;vertical-align:middle">
                <div class="one">
                  <div class="two" id='deepburst_image'><img src='images/deepburst_after.png'></div>
                  <img src='images/deepburst_before.png'>
                </div>
                <script type="text/javascript">
                  function deepburst_start() {
                    document.getElementById('deepburst_image').style.opacity = "1";
                  }

                  function deepburst_stop() {
                    document.getElementById('deepburst_image').style.opacity = "0";
                  }
                  deepburst_stop()
                </script>
              </td>
              <td style="padding:20px;width:75%;vertical-align:middle">
                <a href="https://drive.google.com/file/d/1GAH8ijyZ7GnoBnQFANEzdXinHrE4vvXn/view?usp=sharing">
                  <span class="papertitle">Burst Denoising with Kernel Prediction Networks</span>
                </a>
                <br>
                <a href="https://bmild.github.io/">Ben Mildenhall</a>,
                <strong>Jonathan T. Barron</strong>,
                <a href="http://people.csail.mit.edu/jiawen/">Jiawen Chen</a>,
                <a href="http://www.dsharlet.com/">Dillon Sharlet</a>,
                <a href="http://graphics.stanford.edu/~renng/">Ren Ng</a>, Robert Carroll
                <br>
                <em>CVPR</em>, 2018 &nbsp <font color=#FF8080><strong>(Spotlight)</strong></font>
                <br>
                <a href="https://drive.google.com/file/d/1aqk3Q-L2spjLZh2yRWKUWIDcZkGjQ7US/view?usp=sharing">supplement</a> /
                <a href="https://github.com/google/burst-denoising">code</a> /
                <a href="data/Mildenhall2018.bib">bibtex</a>
                <p></p>
                <p>We train a network to predict linear kernels that denoise noisy bursts from cellphone cameras.</p>
              </td>
            </tr>

            <tr onmouseout="friendly_stop()" onmouseover="friendly_start()">
              <td style="padding:20px;width:25%;vertical-align:middle">
                <div class="one">
                  <div class="two" id='friendly_image'><img src='images/friendly_after.png'></div>
                  <img src='images/friendly_before.png'>
                </div>
                <script type="text/javascript">
                  function friendly_start() {
                    document.getElementById('friendly_image').style.opacity = "1";
                  }

                  function friendly_stop() {
                    document.getElementById('friendly_image').style.opacity = "0";
                  }
                  friendly_stop()
                </script>
              </td>
              <td style="padding:20px;width:75%;vertical-align:middle">
                <a href="https://drive.google.com/file/d/1w_0djhL0QgC_fbehnJ0c-J23_kW_420p/view?usp=sharing">
                  <span class="papertitle">A Hardware-Friendly Bilateral Solver for Real-Time Virtual Reality Video</span>
                </a>
                <br>
                <a href="https://homes.cs.washington.edu/~amrita/">Amrita Mazumdar</a>, <a href="http://homes.cs.washington.edu/~armin/">Armin Alaghi</a>, <strong>Jonathan T. Barron</strong>, <a href="https://www.cs.unc.edu/~gallup/">David Gallup</a>, <a href="https://homes.cs.washington.edu/~luisceze/">Luis Ceze</a>, <a href="https://homes.cs.washington.edu/~oskin/">Mark Oskin</a>, <a href="http://homes.cs.washington.edu/~seitz/">Steven M. Seitz</a>
                <br>
                <em>High-Performance Graphics (HPG)</em>, 2017
                <br>
                <a href="https://sampa.cs.washington.edu/projects/vr-hw.html">project page</a>
                <p></p>
                <p>A reformulation of the bilateral solver can be implemented efficiently on GPUs and FPGAs.</p>
              </td>
            </tr>

            <tr onmouseout="hdrnet_stop()" onmouseover="hdrnet_start()">
              <td style="padding:20px;width:25%;vertical-align:middle">
                <div class="one">
                  <div class="two" id='hdrnet_image'><img src='images/hdrnet_after.jpg'></div>
                  <img src='images/hdrnet_before.jpg'>
                </div>
                <script type="text/javascript">
                  function hdrnet_start() {
                    document.getElementById('hdrnet_image').style.opacity = "1";
                  }

                  function hdrnet_stop() {
                    document.getElementById('hdrnet_image').style.opacity = "0";
                  }
                  hdrnet_stop()
                </script>
              </td>
              <td style="padding:20px;width:75%;vertical-align:middle">
                <a href="https://drive.google.com/file/d/1jQY3CTMnLX7PeGUzYLso9H1eCsZyWbwg/view?usp=sharing">
                  <span class="papertitle">Deep Bilateral Learning for Real-Time Image Enhancement</span>
                </a>
                <br>
                <a href="http://www.mgharbi.com">Micha&euml;l Gharbi</a>, <a href="http://people.csail.mit.edu/jiawen/">Jiawen Chen</a>, <strong>Jonathan T. Barron</strong>, <a href="https://people.csail.mit.edu/hasinoff/">Samuel W. Hasinoff</a>, <a href="http://people.csail.mit.edu/fredo/">Fr&eacute;do Durand </a>
                <br>
                <em>SIGGRAPH</em>, 2017
                <br>
                <a href="https://groups.csail.mit.edu/graphics/hdrnet/">project page</a> /
                <a href="https://www.youtube.com/watch?v=GAe0qKKQY_I">video</a> /
                <a href="data/GharbiSIGGRAPH2017.bib">bibtex</a> /
                <a href="http://news.mit.edu/2017/automatic-image-retouching-phone-0802">p</a><a href="https://www.wired.com/story/googles-new-algorithm-perfects-photos-before-you-even-take-them/">r</a><a href="https://petapixel.com/2017/08/02/new-ai-can-retouch-photos-snap/">e</a><a href="https://www.theverge.com/2017/8/2/16082272/google-mit-retouch-photos-machine-learning">s</a><a href="http://gizmodo.com/clever-camera-app-uses-deep-learning-to-perfectly-retou-1797474282">s</a>
                <p></p>
                <p>By training a deep network in bilateral space we can learn a model for high-resolution and real-time image enhancement.</p>
              </td>
            </tr>

            <tr onmouseout="ffcc_stop()" onmouseover="ffcc_start()">
              <td style="padding:20px;width:25%;vertical-align:middle">
                <div class="one">
                  <div class="two" id='ffcc_image'><img src='images/ffcc_after.jpg'></div>
                  <img src='images/ffcc_before.jpg'>
                </div>
                <script type="text/javascript">
                  function ffcc_start() {
                    document.getElementById('ffcc_image').style.opacity = "1";
                  }

                  function ffcc_stop() {
                    document.getElementById('ffcc_image').style.opacity = "0";
                  }
                  ffcc_stop()
                </script>
              </td>
              <td style="padding:20px;width:75%;vertical-align:middle">
                <a href="https://arxiv.org/abs/1611.07596">
                  <span class="papertitle">Fast Fourier Color Constancy</span>
                </a>
                <br>
                <strong>Jonathan T. Barron</strong>,
                <a href="https://ai.google/research/people/105312/">Yun-Ta Tsai</a>,
                <br>
                <em>CVPR</em>, 2017
                <br>
                <a href="https://youtu.be/rZCXSfl13rY">video</a> /
                <a href="data/BarronTsaiCVPR2017.bib">bibtex</a> /
                <a href="https://github.com/google/ffcc">code</a> /
                <a href="https://drive.google.com/open?id=0B4nuwEMaEsnmWkJQMlFPSFNzbEk">output</a> /
                <a href="https://blog.google/products/photos/six-tips-make-your-photos-pop/">blog post</a> /
                <a href="https://9to5google.com/2017/03/03/google-photos-auto-white-balance/">p</a><a href="https://www.engadget.com/2017/03/03/google-photos-automatically-fixes-your-pictures-white-balance/">r</a><a href="https://lifehacker.com/google-photos-will-now-automatically-adjust-the-white-b-1793009155">e</a><a href="https://petapixel.com/2017/03/06/google-photos-will-now-automatically-white-balance-snapshots/">s</a><a href="http://www.theverge.com/2017/3/3/14800062/google-photos-auto-white-balance-android">s</a>
                <p></p>
                <p>Color space can be aliased, allowing white balance models to be learned and evaluated in the frequency domain. This improves accuracy by 13-20% and speed by 250-3000x.</p>
                <p>This technology is used by <a href="https://store.google.com/product/pixel_compare">Google Pixel</a>, <a href="https://photos.google.com/">Google Photos</a>, and <a href="https://www.google.com/maps">Google Maps</a>.</p>
              </td>
            </tr>

            <tr onmouseout="jump_stop()" onmouseover="jump_start()" bgcolor="#ffffd0">
              <td style="padding:20px;width:25%;vertical-align:middle">
                <div class="one">
                  <div class="two" id='jump_image'><img src='images/jump_anim.gif'></div>
                  <img src='images/jump_still.png'>
                </div>
                <script type="text/javascript">
                  function jump_start() {
                    document.getElementById('jump_image').style.opacity = "1";
                  }

                  function jump_stop() {
                    document.getElementById('jump_image').style.opacity = "0";
                  }
                  jump_stop()
                </script>
              </td>
              <td style="padding:20px;width:75%;vertical-align:middle">
                <a href="https://drive.google.com/file/d/1RBnTrtzqmuO8uj3GQaR5vBJZjIC3Jxjn/view?usp=sharing">
                  <span class="papertitle">Jump: Virtual Reality Video</span>
                </a>
                <br>
                <a href="http://mi.eng.cam.ac.uk/~ra312/">Robert Anderson</a>, <a href="https://www.cs.unc.edu/~gallup/">David Gallup</a>, <strong>Jonathan T. Barron</strong>, <a href="https://mediatech.aalto.fi/~janne/index.php">Janne Kontkanen</a>, <a href="https://www.cs.cornell.edu/~snavely/">Noah Snavely</a>, <a href="http://carlos-hernandez.org/">Carlos Hern&aacutendez</a>, <a href="https://homes.cs.washington.edu/~sagarwal/">Sameer Agarwal</a>, <a href="https://homes.cs.washington.edu/~seitz/">Steven M Seitz</a>
                <br>
                <em>SIGGRAPH Asia</em>, 2016
                <br>
                <a href="https://drive.google.com/file/d/11D4eCDXqqFTtZT0WS2COJE0hsAN3QEww/view?usp=sharing">supplement</a> /
                <a href="https://www.youtube.com/watch?v=O0qUYynupTI">video</a> /
                <a href="data/Anderson2016.bib">bibtex</a> /
                <a href="https://blog.google/products/google-vr/jump-using-omnidirectional-stereo-vr-video/">blog post</a>
                <p></p>
                <p>Using computer vision and a ring of cameras, we can make video for virtual reality headsets that is both stereo and 360&deg;.</p>
                <p>This technology is used by <a href="https://vr.google.com/jump/">Jump</a>. </p>
              </td>
            </tr>

            <tr onmouseout="hdrp_stop()" onmouseover="hdrp_start()">
              <td style="padding:20px;width:25%;vertical-align:middle">
                <div class="one">
                  <div class="two" id='hdrp_image'><img src='images/hdrp_after.jpg'></div>
                  <img src='images/hdrp_before.jpg'>
                </div>
                <script type="text/javascript">
                  function hdrp_start() {
                    document.getElementById('hdrp_image').style.opacity = "1";
                  }

                  function hdrp_stop() {
                    document.getElementById('hdrp_image').style.opacity = "0";
                  }
                  hdrp_stop()
                </script>
              </td>
              <td style="padding:20px;width:75%;vertical-align:middle">
                <a href="https://drive.google.com/file/d/1SSSmVHWbMQ7sZMOredSVWVJXbXobkyzA/view?usp=sharing">
                  <span class="papertitle">Burst Photography for High Dynamic Range and Low-Light Imaging on Mobile Cameras</span>
                </a>
                <br>
                <a href="http://people.csail.mit.edu/hasinoff/">Samuel W. Hasinoff</a>, <a href="http://www.dsharlet.com/">Dillon Sharlet</a>, <a href="http://www.geisswerks.com/">Ryan Geiss</a>, <a href="http://people.csail.mit.edu/abadams/">Andrew Adams</a>, <strong>Jonathan T. Barron</strong>, Florian Kainz, <a href="http://people.csail.mit.edu/jiawen/">Jiawen Chen</a>, <a href="http://graphics.stanford.edu/~levoy/">Marc Levoy</a>
                <br>
                <em>SIGGRAPH Asia</em>, 2016
                <br>
                <a href="http://hdrplusdata.org/">project page</a> /
                <a href="https://drive.google.com/open?id=15EUuSDi1BtHUgQCaiooVrD44qYKIC3vx">supplement</a> /
                <a href="data/Hasinoff2016.bib">bibtex</a>
                <p></p>
                <p>Mobile phones can take beautiful photographs in low-light or high dynamic range environments by aligning and merging a burst of images.</p>
                <p>This technology is used by the <a href="https://research.googleblog.com/2014/10/hdr-low-light-and-high-dynamic-range.html">Nexus HDR+</a> feature.</p>
              </td>
            </tr>

            <tr onmouseout="bs_stop()" onmouseover="bs_start()" bgcolor="#ffffd0">
              <td style="padding:20px;width:25%;vertical-align:middle">
                <div class="one">
                  <div class="two" id='bs_image'><img src='images/BS_after.jpg'></div>
                  <img src='images/BS_before.jpg'>
                </div>
                <script type="text/javascript">
                  function bs_start() {
                    document.getElementById('bs_image').style.opacity = "1";
                  }

                  function bs_stop() {
                    document.getElementById('bs_image').style.opacity = "0";
                  }
                  bs_stop()
                </script>
              </td>
              <td style="padding:20px;width:75%;vertical-align:middle">
                <a href="https://drive.google.com/file/d/1zFzCaFwkGK1EGmJ_KEqb-ZsRJhfUKN2S/view?usp=sharing">
                  <span class="papertitle">The Fast Bilateral Solver</span>
                </a>
                <br>
                <strong>Jonathan T. Barron</strong>,
                <a href="https://cs.stanford.edu/~poole/">Ben Poole</a>
                <br>
                <em>ECCV</em>, 2016 &nbsp <font color="red"><strong>(Oral Presentation, Best Paper Honorable Mention)</strong></font>
                <br>
                <a href="http://arxiv.org/abs/1511.03296">arXiv</a> /
                <a href="data/BarronPooleECCV2016.bib">bibtex</a> /
                <a href="http://videolectures.net/eccv2016_barron_bilateral_solver/">video (they messed up my slides, use &rarr;)</a> /
                <a href="https://drive.google.com/file/d/19x1AeN0PFus6Pjrd8nR-vCmJ6bNEefsC/view?usp=sharing">keynote</a> (or <a href="https://drive.google.com/file/d/1p9nduiymK9jUh7WfwlsMjBfW8RoNe_61/view?usp=sharing">PDF</a>) /
                <a href="https://github.com/poolio/bilateral_solver">code</a> /
                <a href="https://drive.google.com/file/d/0B4nuwEMaEsnmaDI3bm5VeDRxams/view?usp=sharing&resourcekey=0-pmkbnOuy8caA7-3GGSfeNQ">depth super-res results</a> /
                <a href="data/BarronPooleECCV2016_reviews.txt">reviews</a>
                <p></p>
                <p>Our solver smooths things better than other filters and faster than other optimization algorithms, and you can backprop through it.</p>
              </td>
            </tr>

            <tr onmouseout="diverdi_stop()" onmouseover="diverdi_start()">
              <td style="padding:20px;width:25%;vertical-align:middle">
                <div class="one">
                  <div class="two" id='diverdi_image'><img src='images/diverdi_after.jpg'></div>
                  <img src='images/diverdi_before.jpg'>
                </div>
                <script type="text/javascript">
                  function diverdi_start() {
                    document.getElementById('diverdi_image').style.opacity = "1";
                  }

                  function diverdi_stop() {
                    document.getElementById('diverdi_image').style.opacity = "0";
                  }
                  diverdi_stop()
                </script>
              </td>
              <td style="padding:20px;width:75%;vertical-align:middle">
                <a href="https://drive.google.com/file/d/1mmT-LuK_eBZsl3qp4-fAshEPdgfbgvNE/view?usp=sharing">
                  <span class="papertitle">Geometric Calibration for Mobile, Stereo, Autofocus Cameras</span>
                </a>
                <br>
                <a href="http://www.stephendiverdi.com/">Stephen DiVerdi</a>,
                <strong>Jonathan T. Barron</strong>
                <br>
                <em>WACV</em>, 2016
                <br>
                <a href="data/Diverdi2016.bib">bibtex</a>
                <p></p>
                <p>Standard techniques for stereo calibration don't work for cheap mobile cameras.</p>
              </td>
            </tr>

            <tr onmouseout="dt_stop()" onmouseover="dt_start()">
              <td style="padding:20px;width:25%;vertical-align:middle">
                <div class="one">
                  <div class="two" id='dt_image'><img src='images/DT_edge.jpg'></div>
                  <img src='images/DT_image.jpg'>
                </div>
                <script type="text/javascript">
                  function dt_start() {
                    document.getElementById('dt_image').style.opacity = "1";
                  }

                  function dt_stop() {
                    document.getElementById('dt_image').style.opacity = "0";
                  }
                  dt_stop()
                </script>
              </td>
              <td style="padding:20px;width:75%;vertical-align:middle">
                <a href="https://drive.google.com/file/d/178Xj2PZ1w6hZJpucU-TiZOoCemJmvsVQ/view?usp=sharing">
                  <span class="papertitle">Semantic Image Segmentation with Task-Specific Edge Detection Using CNNs and a Discriminatively Trained Domain Transform</span>
                </a>
                <br>
                <em>CVPR</em>, 2016
                <br>
                <a href="http://liangchiehchen.com/">Liang-Chieh Chen</a>, <strong>Jonathan T. Barron</strong>, <a href="http://ttic.uchicago.edu/~gpapan/">George Papandreou</a>, <a href="http://www.cs.ubc.ca/~murphyk/">Kevin Murphy</a>, <a href="http://www.stat.ucla.edu/~yuille/">Alan L. Yuille</a>
                <br>
                <a href="data/Chen2016.bib">bibtex</a> /
                <a href="http://liangchiehchen.com/projects/DeepLab.html">project page</a> /
                <a href="https://bitbucket.org/aquariusjay/deeplab-public-ver2">code</a>
                <p></p>
                <p>By integrating an edge-aware filter into a convolutional neural network we can learn an edge-detector while improving semantic segmentation.</p>
              </td>
            </tr>

            <tr onmouseout="ccc_stop()" onmouseover="ccc_start()" bgcolor="#ffffd0">
              <td style="padding:20px;width:25%;vertical-align:middle">
                <div class="one">
                  <div class="two" id='ccc_image'><img src='images/ccc_after.jpg'></div>
                  <img src='images/ccc_before.jpg'>
                </div>
                <script type="text/javascript">
                  function ccc_start() {
                    document.getElementById('ccc_image').style.opacity = "1";
                  }

                  function ccc_stop() {
                    document.getElementById('ccc_image').style.opacity = "0";
                  }
                  ccc_stop()
                </script>
              </td>
              <td style="padding:20px;width:75%;vertical-align:middle">
                <a href="https://drive.google.com/file/d/1id74VNDL8ACrrWf6vYgN2M4kS8gd4n7w/view?usp=sharing">
                  <span class="papertitle">Convolutional Color Constancy</span>
                </a>
                <br>
                <strong>Jonathan T. Barron</strong>
                <br>
                <em>ICCV</em>, 2015
                <br>
                <a href="https://drive.google.com/file/d/1vO3sVOMihmpNqsuASeR46Y_iME0lOANR/view?usp=sharing">supplement</a> / <a href="data/BarronICCV2015.bib">bibtex</a> / <a href="https://youtu.be/saHwKY9rfx0">video</a> (or <a href="https://drive.google.com/file/d/0B4nuwEMaEsnmalBNUzlENUJSVDg/view?usp=sharing">mp4</a>)
                <p></p>
                <p>By framing white balance as a chroma localization task we can discriminatively learn a color constancy model that beats the state-of-the-art by 40%.</p>
              </td>
            </tr>

            <tr>
              <td style="padding:20px;width:25%;vertical-align:middle">
                <img src='images/Shelhamer2015.jpg'>
              </td>
              <td style="padding:20px;width:75%;vertical-align:middle">
                <a href="https://drive.google.com/file/d/1stygV71uBruD7Ck9CaAQr7nREvr3DtUL/view?usp=sharing">
                  <span class="papertitle">Scene Intrinsics and Depth from a Single Image</span>
                </a>
                <br>
                <a href="http://imaginarynumber.net/">Evan Shelhamer</a>, <strong>Jonathan T. Barron</strong>, <a href="http://www.eecs.berkeley.edu/%7Etrevor/">Trevor Darrell</a>
                <br>
                <em>ICCV Workshop</em>, 2015
                <br>
                <a href="data/Shelhamer2015.bib">bibtex</a>
                <p></p>
                <p>The monocular depth estimates produced by fully convolutional networks can be used to inform intrinsic image estimation.</p>
              </td>
            </tr>

            <tr bgcolor="#ffffd0" onmouseout="defocus_stop()" onmouseover="defocus_start()">
              <td style="padding:20px;width:25%;vertical-align:middle">
                <div id='lens_blurry' class='hidden'><img src="images/BarronCVPR2015_anim.gif"></div>
                <div id='lens_sharp'>
                  <a href="images/BarronCVPR2015_anim.gif"><img src="images/BarronCVPR2015_still.jpg"></a>
                </div>
                <script type="text/javascript">
                  function defocus_start() {
                    document.getElementById('lens_blurry').style.display = 'inline';
                    document.getElementById('lens_sharp').style.display = 'none';
                  }

                  function defocus_stop() {
                    document.getElementById('lens_blurry').style.display = 'none';
                    document.getElementById('lens_sharp').style.display = 'inline';
                  }
                  defocus_stop()
                </script>
              </td>
              <td style="padding:20px;width:75%;vertical-align:middle">
                <a href="https://drive.google.com/file/d/1R4RdaBZIs-uJobhIFs9yKf3jIsaHQNH0/view?usp=sharing">
                  <span class="papertitle">Fast Bilateral-Space Stereo for Synthetic Defocus</span>
                </a>
                <br>
                <strong>Jonathan T. Barron</strong>, <a href="http://people.csail.mit.edu/abadams/">Andrew Adams</a>, <a href="http://people.csail.mit.edu/yichangshih/">YiChang Shih</a>, <a href="http://carlos-hernandez.org/">Carlos Hern&aacutendez</a>
                <br>
                <em>CVPR</em>, 2015 &nbsp <font color="red"><strong>(Oral Presentation)</strong></font>
                <br>
                <a href="https://drive.google.com/file/d/125qgMdqeT1vojMIijIKcOF099LjUgUOL/view?usp=sharing">abstract</a> /
                <a href="https://drive.google.com/file/d/1HGGvVOGxmPjvgdK5q3UD1Qb5Nttg6kq9/view?usp=sharing">supplement</a> /
                <a href="data/BarronCVPR2015.bib">bibtex</a> /
                <a href="http://techtalks.tv/talks/fast-bilateral-space-stereo-for-synthetic-defocus/61624/">talk</a> /
                <a href="https://drive.google.com/file/d/0B4nuwEMaEsnmSzZZdUJSMllSUkE/view?usp=sharing">keynote</a> (or <a href="https://drive.google.com/open?id=0B4nuwEMaEsnmZ1ZXUzBCWDJYeFU">PDF</a>)
                <p></p>
                <p>By embedding a stereo optimization problem in "bilateral-space" we can very quickly solve for an edge-aware depth map, letting us render beautiful depth-of-field effects.</p>
                <p>This technology is used by the <a href="http://googleresearch.blogspot.com/2014/04/lens-blur-in-new-google-camera-app.html">Google Camera "Lens Blur"</a> feature. </p>
              </td>
            </tr>

            <tr>
              <td style="padding:20px;width:25%;vertical-align:middle">
                <img src="images/PABMM2015.jpg" alt="PontTuset" width="160" style="border-style: none">
              </td>
              <td width="75%" valign="middle">
                <a href="https://arxiv.org/abs/1503.00848" id="MCG_journal">
                  <span class="papertitle">Multiscale Combinatorial Grouping for Image Segmentation and Object Proposal Generation</span>
                </a>
                <br>
                <a href="http://imatge.upc.edu/web/people/jordi-pont-tuset">Jordi Pont-Tuset</a>, <a href="http://www.cs.berkeley.edu/~arbelaez/">Pablo Arbel&aacuteez</a>, <strong>Jonathan T. Barron</strong>, <a href="http://imatge.upc.edu/web/ferran">Ferran Marqu&eacutes</a>, <a href="http://www.cs.berkeley.edu/~malik/">Jitendra Malik</a>
                <br>
                <em>TPAMI</em>, 2017
                <br>
                <a href="http://www.eecs.berkeley.edu/Research/Projects/CS/vision/grouping/mcg/">project page</a> /
                <a href="data/PontTusetTPAMI2017.bib">bibtex</a> /
                <a href="https://drive.google.com/file/d/1AiB78Fy7QVA3KqgcooyzMAC5L8HhNzjz/view?usp=sharing">fast eigenvector code</a>
                <p></p>
                <p>We produce state-of-the-art contours, regions and object candidates, and we compute normalized-cuts eigenvectors 20&times faster.</p>
                <p>This paper subsumes our CVPR 2014 paper.</p>
              </td>
            </tr>

            <tr bgcolor="#ffffd0" onmouseout="sirfs_stop()" onmouseover="sirfs_start()">
              <td style="padding:20px;width:25%;vertical-align:middle">
                <div class="one">
                  <div class="two" id='sirfs_image'>
                    <a href="images/Estee.png"><img src='images/Estee_160.png' style="border-style: none"></a>
                  </div>
                  <a href="images/Estee.png"><img src='images/Estee_160_prodB2.png' style="border-style: none"></a>
                </div>
                <script type="text/javascript">
                  function sirfs_start() {
                    document.getElementById('sirfs_image').style.opacity = "1";
                  }

                  function sirfs_stop() {
                    document.getElementById('sirfs_image').style.opacity = "0";
                  }
                  sirfs_stop()
                </script>
              </td>
              <td width="75%" valign="middle">
                <p>
                  <a href="https://arxiv.org/abs/2010.03592" id="SIRFS">
                    <span class="papertitle">Shape, Illumination, and Reflectance from Shading</span>
                  </a>
                  <br>
                  <strong>Jonathan T. Barron</strong>, <a href="http://www.cs.berkeley.edu/~malik/">Jitendra Malik</a>
                  <br>
                  <em>TPAMI</em>, 2015
                  <br>
                  <a href="data/BarronMalikTPAMI2015.bib">bibtex</a> / <a href="https://drive.google.com/file/d/0B4nuwEMaEsnmVWpfa19mbUxIYW8/view?usp=sharing">keynote</a> (or <a href="https://drive.google.com/file/d/0B4nuwEMaEsnmazJvLXJUb0NuM1U/view?usp=sharing">powerpoint</a>, <a href="https://drive.google.com/file/d/0B4nuwEMaEsnmTDBUWE96VHJndjg/view?usp=sharing">PDF</a>) / <a href="http://www.youtube.com/watch?v=NnePYprvFvA">video</a> / <a href="https://drive.google.com/file/d/1vg9Rb-kBntSTnTCzVgFlskkPXvTB_5aq/view?usp=sharing">code &amp; data</a> / <a href="https://drive.google.com/file/d/11X5Zfjy7Q7oP_V2rtqy2f5-x9YgQUAFd/view?usp=sharing">kudos</a>
                </p>
                <p>
                  We present <strong>SIRFS</strong>, which can estimate shape, chromatic illumination, reflectance, and shading from a single image of an masked object.
                </p>
                <p>
                  This paper subsumes our CVPR 2011, CVPR 2012, and ECCV 2012 papers.
                </p>
              </td>
            </tr>

            <tr>
              <td style="padding:20px;width:25%;vertical-align:middle">
                <img src="images/ArbalaezCVPR2014.jpg" alt="ArbalaezCVPR2014" width="160" height="120" style="border-style: none">
              </td>
              <td width="75%" valign="middle">
                <a href="https://drive.google.com/file/d/1M0wijHY134F9ETBgO8mjeuKUSblTRLG0/view?usp=sharing">
                  <span class="papertitle">Multiscale Combinatorial Grouping</span>
                </a>
                <br>
                <a href="http://www.cs.berkeley.edu/~arbelaez/">Pablo Arbel&aacuteez</a>, <a href="http://imatge.upc.edu/web/people/jordi-pont-tuset">Jordi Pont-Tuset</a>, <strong>Jonathan T. Barron</strong>, <a href="http://imatge.upc.edu/web/ferran">Ferran Marqu&eacutes</a>, <a href="http://www.cs.berkeley.edu/~malik/">Jitendra Malik</a>
                <br>
                <em>CVPR</em>, 2014
                <br>
                <a href="http://www.eecs.berkeley.edu/Research/Projects/CS/vision/grouping/mcg/">project page</a> /
                <a href="data/ArbelaezCVPR2014.bib">bibtex</a>
                <p>This paper is subsumed by <a href="#MCG_journal">our journal paper</a>.</p>
              </td>
            </tr>

            <tr onmouseout="flyspin_stop()" onmouseover="flyspin_start()">
              <td style="padding:20px;width:25%;vertical-align:middle">
                <div id='flyspin' class='hidden'><img src="images/BarronICCV2013_160.gif"></div>
                <div id='flystill'>
                  <a href="images/BarronICCV2013.gif"><img src="images/BarronICCV2013_160.jpg"></a>
                </div>
                <script type="text/javascript">
                  function flyspin_start() {
                    document.getElementById('flyspin').style.display = 'inline';
                    document.getElementById('flystill').style.display = 'none';
                  }

                  function flyspin_stop() {
                    document.getElementById('flyspin').style.display = 'none';
                    document.getElementById('flystill').style.display = 'inline';
                  }
                  flyspin_stop()
                </script>
              </td>
              <td width="75%" valign="middle">
                <a href="https://drive.google.com/file/d/1shvItvx_8Sb8QNXhrOXkuRmx2618iwNJ/view?usp=sharing">
                  <span class="papertitle">Volumetric Semantic Segmentation using Pyramid Context Features</span>
                </a>
                <br>
                <strong>Jonathan T. Barron</strong>, <a href="http://www.cs.berkeley.edu/~arbelaez/">Pablo Arbel&aacuteez</a>, <a href="http://big.lbl.gov/">Soile V. E. Ker&aumlnen</a>, <a href="http://www.lbl.gov/gsd/biggin.html">Mark D. Biggin</a>,
                <br> <a href="http://dwknowles.lbl.gov/">David W. Knowles</a>, <a href="http://www.cs.berkeley.edu/~malik/">Jitendra Malik</a>
                <br>
                <em>ICCV</em>, 2013
                <br>
                <a href="https://drive.google.com/file/d/1htiLpMAcYLtuBthmAb4XHnOYxUbkfnqR/view?usp=sharing">supplement</a> /
                <a href="https://drive.google.com/file/d/1qoYeFNa443myn2SfcdhmCsYBqE9xQrPD/view?usp=sharing">poster</a> /
                <a href="data/BarronICCV2013.bib">bibtex</a> / <a href="http://www.youtube.com/watch?v=Y56-FcfnlVA&hd=1">video 1</a> (or <a href="https://drive.google.com/file/d/0B4nuwEMaEsnmZ1ZLaHdQYzAxNlU/view?usp=sharing">mp4</a>) / <a href="http://www.youtube.com/watch?v=mvRoYuP6-l4&hd=1">video 2</a> (or <a href="https://drive.google.com/file/d/0B4nuwEMaEsnmZ1ZLaHdQYzAxNlU/view?usp=sharing">mp4</a>) / <a href="https://drive.google.com/file/d/0B4nuwEMaEsnmSF9YdWJjQmh4QW8/view?usp=sharing">code &amp; data</a>
                <p>
                  We present a technique for efficient per-voxel linear classification, which enables accurate and fast semantic segmentation of volumetric Drosophila imagery.
                </p>
              </td>
            </tr>

            <tr>
              <td style="padding:20px;width:25%;vertical-align:middle">
                <img src="images/3DSP_160.jpg" alt="3DSP" width="160" height="120" style="border-style: none">
              </td>
              <td width="75%" valign="middle">
                <a href="https://drive.google.com/file/d/0B4nuwEMaEsnmbG1tOGIta3N1Wjg/view?usp=sharing" id="3DSP">
                  <span class="papertitle">3D Self-Portraits</span>
                </a>
                <br>
                <a href="http://www.hao-li.com/">Hao Li</a>, <a href="http://www.evouga.com/">Etienne Vouga</a>, Anton Gudym, <a href="http://www.cs.princeton.edu/~linjiel/">Linjie Luo</a>, <strong>Jonathan T. Barron</strong>, Gleb Gusev
                <br>
                <em>SIGGRAPH Asia</em>, 2013
                <br>
                <a href="http://www.youtube.com/watch?v=DmUkbZ0QMCA">video</a> / <a href="http://shapify.me/">shapify.me</a> / <a href="data/3DSP_siggraphAsia2013.bib">bibtex</a>
                <p>Our system allows users to create textured 3D models of themselves in arbitrary poses using only a single 3D sensor.</p>
              </td>
            </tr>

            <tr onmouseout="rgbd_stop()" onmouseover="rgbd_start()">
              <td style="padding:20px;width:25%;vertical-align:middle">
                <div id='rgbd_anim' class='hidden'><img src="images/SceneSIRFS.gif"></div>
                <div id='rgbd_still'><img src="images/SceneSIRFS-still.jpg"></div>
                <script type="text/javascript">
                  function rgbd_start() {
                    document.getElementById('rgbd_anim').style.display = 'inline';
                    document.getElementById('rgbd_still').style.display = 'none';
                  }

                  function rgbd_stop() {
                    document.getElementById('rgbd_anim').style.display = 'none';
                    document.getElementById('rgbd_still').style.display = 'inline';
                  }
                  rgbd_stop()
                </script>
              </td>
              <td width="75%" valign="middle">
                <a href="https://drive.google.com/file/d/1snypSLhzC0jXCchJRsWpcDZ7Es5hDmXo/view?usp=sharing">
                  <span class="papertitle">Intrinsic Scene Properties from a Single RGB-D Image</span>
                </a>
                <br>
                <strong>Jonathan T. Barron</strong>, <a href="http://www.cs.berkeley.edu/~malik/">Jitendra Malik</a>
                <br>
                <em>CVPR</em>, 2013 &nbsp <font color="red"><strong>(Oral Presentation)</strong></font>
                <br>
                <a href="https://drive.google.com/file/d/1cLUw72WpgdZ_3TQAjJABdgywqjBfn_Mq/view?usp=sharing">supplement</a> / <a href="data/BarronMalikCVPR2013.bib">bibtex</a> / <a href="http://techtalks.tv/talks/intrinsic-scene-properties-from-a-single-rgb-d-image/58614/">talk</a> / <a href="https://drive.google.com/file/d/0B4nuwEMaEsnmWW1CZGJPbi12R0k/view?usp=sharing">keynote</a> (or <a href="https://drive.google.com/file/d/19q3EFf6GIb4UFcCN2DVU2jVKpxRj5kxf/view?usp=sharing">powerpoint</a>, <a href="https://drive.google.com/file/d/0B4nuwEMaEsnmMzQ4ZVp1SWdnVkk/view?usp=sharing">PDF</a>) / <a href="https://drive.google.com/open?id=1ZbPScVA6Efqd-ESvojl92sw8K-82Xxry">code &amp; data</a>
                <p>By embedding mixtures of shapes &amp; lights into a soft segmentation of an image, and by leveraging the output of the Kinect, we can extend SIRFS to scenes.
                  <br>
                  <br>TPAMI Journal version: <a href="https://drive.google.com/file/d/1iQiUxZvjPPnb8rFCwXYesTgFSRk7mkAq/view?usp=sharing">version</a> / <a href="data/BarronMalikTPAMI2015B.bib">bibtex</a>
                </p>
              </td>
            </tr>

            <tr>
              <td style="padding:20px;width:25%;vertical-align:middle">
                <img src="images/Boundary.jpg" alt="Boundary_png" style="border-style: none">
              </td>
              <td width="75%" valign="middle">
                <a href="https://drive.google.com/file/d/1H4YPovfrvcce3HGMEhidwU2l2fTcNR5y/view?usp=sharing">
                  <span class="papertitle">Boundary Cues for 3D Object Shape Recovery</span>
                </a>
                <br>
                <a href="http://www.kevinkarsch.com/">Kevin Karsch</a>,
                <a href="http://web.engr.illinois.edu/~liao17/">Zicheng Liao</a>,
                <a href="http://web.engr.illinois.edu/~jjrock2/">Jason Rock</a>,
                <strong>Jonathan T. Barron</strong>,
                <a href="http://www.cs.illinois.edu/homes/dhoiem/">Derek Hoiem</a>
                <br>
                <em>CVPR</em>, 2013
                <br>
                <a href="https://drive.google.com/file/d/0B4nuwEMaEsnmLUQ5SVJTcUZIYXc/view?usp=sharing">supplement</a> / <a href="data/KarschCVPR2013.bib">bibtex</a>
                <p>Boundary cues (like occlusions and folds) can be used for shape reconstruction, which improves object recognition for humans and computers.</p>
              </td>
            </tr>

            <tr onmouseout="eccv12_stop()" onmouseover="eccv12_start()">
              <td style="padding:20px;width:25%;vertical-align:middle">
                <div id='eccv12_anim' class='hidden'>
                  <a href="https://drive.google.com/file/d/1brxb58CfRPe7KEER4Q_fYS9B_J-hiS0t/view?usp=sharing"><img src="images/ECCV2012_small.gif"></a>
                </div>
                <div id='eccv12_still'><img src="images/ECCV2012_still.jpg"></div>
                <script type="text/javascript">
                  function eccv12_start() {
                    document.getElementById('eccv12_anim').style.display = 'inline';
                    document.getElementById('eccv12_still').style.display = 'none';
                  }

                  function eccv12_stop() {
                    document.getElementById('eccv12_anim').style.display = 'none';
                    document.getElementById('eccv12_still').style.display = 'inline';
                  }
                  eccv12_stop()
                </script>
              </td>
              <td width="75%" valign="middle">
                <a href="https://drive.google.com/file/d/1NczR4pJ-s0YBjCe0rCevMt8IM5JPuUrc/view?usp=sharing">
                  <span class="papertitle">Color Constancy, Intrinsic Images, and Shape Estimation</span>
                </a>
                <br>
                <strong>Jonathan T. Barron</strong>, <a href="http://www.cs.berkeley.edu/~malik/">Jitendra Malik</a>
                <br>
                <em>ECCV</em>, 2012
                <br>
                <a href="https://drive.google.com/file/d/1zuxhWZ3i6THvuRRBeE7dM_BJfDxO72Fq/view?usp=sharing">supplement</a> /
                <a href="data/BarronMalikECCV2012.bib">bibtex</a> /
                <a href="https://drive.google.com/file/d/12x8mhqpFsA6p0u6ZQW-ieRKF8hlQBKKe/view?usp=sharing">poster</a> /
                <a href="http://www.youtube.com/watch?v=NnePYprvFvA">video</a>
                <p>This paper is subsumed by <a href="#SIRFS">SIRFS</a>.</p>
              </td>
            </tr>

            <tr onmouseout="cvpr12_stop()" onmouseover="cvpr12_start()">
              <td style="padding:20px;width:25%;vertical-align:middle">
                <div class="one" style="height: 120px">
                  <div class="two" id='cvpr12_image' style="height: 120px">
                    <img src='images/BarronCVPR2012_after.jpg' style="border-style: none">
                  </div>
                  <img src='images/BarronCVPR2012_before.jpg' style="border-style: none">
                </div>
                <script type="text/javascript">
                  function cvpr12_start() {
                    document.getElementById('cvpr12_image').style.opacity = "1";
                  }

                  function cvpr12_stop() {
                    document.getElementById('cvpr12_image').style.opacity = "0";
                  }
                  cvpr12_stop()
                </script>
              </td>
              <td width="75%" valign="middle">
                <a href="https://drive.google.com/file/d/17RfINbE2dr2EjXp9MtGO0MHJLQmQVhvT/view?usp=sharing">
                  <span class="papertitle">Shape, Albedo, and Illumination from a Single Image of an Unknown Object</span>
                </a>
                <br>
                <strong>Jonathan T. Barron</strong>, <a href="http://www.cs.berkeley.edu/~malik/">Jitendra Malik</a>
                <br>
                <em>CVPR</em>, 2012
                <br>
                <a href="https://drive.google.com/file/d/1Im_bUI42AP9VPoNtsjLajvtLRiwv39k3/view?usp=sharing">supplement</a> /
                <a href="data/BarronMalikCVPR2012.bib">bibtex</a> /
                <a href="https://drive.google.com/file/d/1IAlSF4k3_CEL9dfbaMiNTFPBoEkLhsRl/view?usp=sharing">poster</a>
                <p>This paper is subsumed by <a href="#SIRFS">SIRFS</a>.</p>
              </td>
            </tr>

            <tr>
              <td style="padding:20px;width:25%;vertical-align:middle">
                <img src="images/B3DO.jpg" alt="b3do" width="160" style="border-style: none">
              </td>
              <td width="75%" valign="middle">
                <a href="https://drive.google.com/file/d/1_S8EQyngbHQrB415o0XkQ4V9SMzdEgWT/view?usp=sharing">
                  <span class="papertitle">A Category-Level 3-D Object Dataset: Putting the Kinect to Work</span>
                </a>
                <br>
                <a href="http://www.eecs.berkeley.edu/%7Eallie/">Allison Janoch</a>,
                <a href="http://sergeykarayev.com/">Sergey Karayev</a>,
                <a href="http://www.eecs.berkeley.edu/%7Ejiayq/">Yangqing Jia</a>,
                <strong>Jonathan T. Barron</strong>,
                <a href="http://www.cs.berkeley.edu/%7Emfritz/">Mario Fritz</a>,
                <a href="http://www.icsi.berkeley.edu/%7Esaenko/">Kate Saenko</a>,
                <a href="http://www.eecs.berkeley.edu/%7Etrevor/">Trevor Darrell</a>
                <br>
                <em>ICCV 3DRR Workshop</em>, 2011
                <br>
                <a href="data/B3DO_ICCV_2011.bib">bibtex</a> /
                <a href="https://drive.google.com/file/d/1qf4-U5RhSw12O7gzQwW66SMQhs2FWYDW/view?usp=sharing">"smoothing" code</a>
                <p>We present a large RGB-D dataset of indoor scenes and investigate ways to improve object detection using depth information.</p>
              </td>
            </tr>

            <tr>
              <td style="padding:20px;width:25%;vertical-align:middle">
                <img src="images/safs.jpg" alt="safs_small" width="160" height="160" style="border-style: none">
              </td>
              <td width="75%" valign="middle">
                <a href="https://drive.google.com/file/d/1EZTOO5xezLYcyIFgAzs4KuZFLbTcwTDH/view?usp=sharing">
                  <span class="papertitle">High-Frequency Shape and Albedo from Shading using Natural Image Statistics</span>
                </a>
                <br>
                <strong>Jonathan T. Barron</strong>, <a href="http://www.cs.berkeley.edu/~malik/">Jitendra Malik</a>
                <br>
                <em>CVPR</em>, 2011
                <br>
                <a href="data/BarronMalikCVPR2011.bib">bibtex</a>
                <p>This paper is subsumed by <a href="#SIRFS">SIRFS</a>.</p>
              </td>
            </tr>

            <tr>
              <td style="padding:20px;width:25%;vertical-align:middle">
                <img src="images/fast_texture.jpg" alt="fast-texture" width="160" height="160">
              </td>
              <td width="75%" valign="middle">
                <a href="https://drive.google.com/file/d/1rc05NatkQVmUDlGCAYcHSrvAzTpU9knT/view?usp=sharing">
                  <span class="papertitle">Discovering Efficiency in Coarse-To-Fine Texture Classification</span>
                </a>
                <br>
                <strong>Jonathan T. Barron</strong>, <a href="http://www.cs.berkeley.edu/~malik/">Jitendra Malik</a>
                <br>
                <em>Technical Report</em>, 2010
                <br>
                <a href="data/BarronTR2010.bib">bibtex</a>
                <p>A model and feature representation that allows for sub-linear coarse-to-fine semantic segmentation.
                </p>
              </td>
            </tr>

            <tr>
              <td style="padding:20px;width:25%;vertical-align:middle">
                <img src="images/prl.jpg" alt="prl" width="160" height="160">
              </td>
              <td width="75%" valign="middle">
                <a href="https://drive.google.com/file/d/13rVuJpcytRdLYCnKpq46g7B7IzSrPQ2P/view?usp=sharing">
                  <span class="papertitle">Parallelizing Reinforcement Learning</span>
                </a>
                <br>
                <strong>Jonathan T. Barron</strong>, <a href="http://www.eecs.berkeley.edu/~dsg/">Dave Golland</a>, <a href="http://www.cs.berkeley.edu/~nickjhay/">Nicholas J. Hay</a>
                <br>
                <em>Technical Report</em>, 2009
                <br>
                <a href="data/BarronPRL2009.bib">bibtex</a>
                <p>Markov Decision Problems which lie in a low-dimensional latent space can be decomposed, allowing modified RL algorithms to run orders of magnitude faster in parallel.</p>
              </td>
            </tr>

            <tr>
              <td style="padding:20px;width:25%;vertical-align:middle">
                <img src="images/bd_promo.jpg" alt="blind-date" width="160" height="160">
              </td>
              <td width="75%" valign="middle">
                <a href="https://drive.google.com/file/d/1PQjzKgFcrAesMIDJr-WDlCwuGUxZJZwO/view?usp=sharing">
                  <span class="papertitle">Blind Date: Using Proper Motions to Determine the Ages of Historical Images</span>
                </a>
                <br>
                <strong>Jonathan T. Barron</strong>, <a href="http://cosmo.nyu.edu/hogg/">David W. Hogg</a>, <a href="http://www.astro.princeton.edu/~dstn/">Dustin Lang</a>, <a href="http://cs.nyu.edu/~roweis/">Sam Roweis</a>
                <br>
                <em>The Astronomical Journal</em>, 136, 2008
                <p>Using the relative motions of stars we can accurately estimate the date of origin of historical astronomical images.</p>
              </td>
            </tr>

            <tr>
              <td style="padding:20px;width:25%;vertical-align:middle">
                <img src="images/clean_promo.jpg" alt="clean-usnob" width="160" height="160">
              </td>
              <td width="75%" valign="middle">
                <a href="https://drive.google.com/file/d/1YvRx-4hrZoCk-nl6OgVJZlHAqOiN5hWq/view?usp=sharing">
                  <span class="papertitle">Cleaning the USNO-B Catalog Through Automatic Detection of Optical Artifacts</span>
                </a>
                <br>
                <strong>Jonathan T. Barron</strong>, <a href="http://stumm.ca/">Christopher Stumm</a>, <a href="http://cosmo.nyu.edu/hogg/">David W. Hogg</a>, <a href="http://www.astro.princeton.edu/~dstn/">Dustin Lang</a>, <a href="http://cs.nyu.edu/~roweis/">Sam Roweis</a>
                <br>
                <em>The Astronomical Journal</em>, 135, 2008
                <p>We use computer vision techniques to identify and remove diffraction spikes and reflection halos in the USNO-B Catalog.</p>
                <p>In use at <a href="http://www.astrometry.net">Astrometry.net</a></p>
              </td>
            </tr>

          </tbody></table>

          
          <table width="100%" align="center" border="0" cellspacing="0" cellpadding="20"><tbody>
            <tr>
              <td>
                <h2>Miscellanea</h2>
              </td>
            </tr>
          </tbody></table>
          <table width="100%" align="center" border="0" cellpadding="20"><tbody>
            
            <tr>
              <td style="padding:20px;width:25%;vertical-align:middle"><img src="images/cvf.jpg"></td>
              <td width="75%" valign="center">
                <a href="https://cvpr2023.thecvf.com/Conferences/2023/Organizers">Demo Chair, CVPR 2023</a>
          <br>
                <a href="https://cvpr2022.thecvf.com/area-chairs">Area Chair, CVPR 2022</a>
                <br>
                <a href="http://cvpr2021.thecvf.com/area-chairs">Area Chair & Longuet-Higgins Award Committee Member, CVPR 2021</a>
                <br>
                <a href="http://cvpr2019.thecvf.com/area_chairs">Area Chair, CVPR 2019</a>
                <br>
                <a href="http://cvpr2018.thecvf.com/organizers/area_chairs">Area Chair, CVPR 2018</a>
              </td>
            </tr>
            <tr>
              <td style="padding:20px;width:25%;vertical-align:middle">
                <img src="images/cs188.jpg" alt="cs188">
              </td>
              <td width="75%" valign="center">
                <a href="http://inst.eecs.berkeley.edu/~cs188/sp11/announcements.html">Graduate Student Instructor, CS188 Spring 2011</a>
                <br>
                <a href="http://inst.eecs.berkeley.edu/~cs188/fa10/announcements.html">Graduate Student Instructor, CS188 Fall 2010</a>
                <br>
                <a href="http://aima.cs.berkeley.edu/">Figures, "Artificial Intelligence: A Modern Approach", 3rd Edition</a>
              </td>
            </tr>
            

            <tr>
              <td align="center" style="padding:20px;width:25%;vertical-align:middle">
                <h2>Basically <br> Blog Posts</h2>
              </td>
              <td width="75%" valign="middle">
                <a href="https://arxiv.org/abs/2112.11687">Squareplus: A Softplus-Like Algebraic Rectifier</a>
                <br>
                <a href="https://arxiv.org/abs/2010.09714">A Convenient Generalization of Schlick's Bias and Gain Functions</a>
                <br>
                <a href="https://arxiv.org/abs/1704.07483">Continuously Differentiable Exponential Linear Units</a>
                <br>
                <a href="https://jonbarron.info/data/cvpr2023_llm_workshop_annotated.pdf">Scholars & Big Models: How Can Academics Adapt?</a>
              </td>
            </tr>
            
            
          </tbody></table>
          <table style="width:100%;border:0px;border-spacing:0px;border-collapse:separate;margin-right:auto;margin-left:auto;"><tbody>
            <tr>
              <td style="padding:0px">
                <br>
                <p style="text-align:right;font-size:small;">
                  Feel free to steal this website's <a href="https://github.com/jonbarron/jonbarron_website">source code</a>. <strong>Do not</strong> scrape the HTML from this page itself, as it includes analytics tags that you do not want on your own website &mdash; use the github code instead. Also, consider using <a href="https://leonidk.com/">Leonid Keselman</a>'s <a href="https://github.com/leonidk/new_website">Jekyll fork</a> of this page.
                </p>
              </td>
            </tr>
          </tbody></table>
        </td>
      </tr>
    </table>
  </body>
</html>
