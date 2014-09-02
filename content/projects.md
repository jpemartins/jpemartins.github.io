---
title: Projects
created_at: 2014-05-03 18:30:09 +0200
kind: projects
---

*Here you can find some of the projects that I spend my time on.*

Virtualization / Operating Systems
----------------------------------

<h3 class="project">
<a href="https://github.com/cnplab/clickos"><code>ClickOS</code></a>
<a href="https://github.com/cnplab/clickos" class="github-button" data-icon="octicon-star"
  data-count-href="/cnplab/clickos/stargazers" data-count-api="/repos/cnplab/clickos#stargazers_count">Star</a>

<a href="https://github.com/cnplab/mini-os"><code>    MiniOS</code></a>
<a href="https://github.com/cnplab/mini-os" class="github-button" data-icon="octicon-star"
  data-count-href="/cnplab/mini-os/stargazers" data-count-api="/repos/cnplab/mini-os#stargazers_count">Star</a>

</h3>

A minimalistic operating system to do packet processing using
Click Modular Router. It is built on top of MiniOS and focused on specialization of the VM to have blazzing fast network functions that can be deployed in todays clouds. 
<p><b><u>It is now distributed with the oficial Click sources as a MiniOS driver!</u></b></p>

<h3 class="project">
<a href="https://github.com/cnplab/xennet"><code>xennet</code></a>
</h3>

Modifications I did to Xen netback/netfront for Linux/MiniOS/FreeBSD
in order to get 10 Gbit/s throughtput for almost all packet sizes.

<h3 class="project">
<a href="https://github.com/cnplab/cosmos"><code>cosmos</code></a>
</h3>

Toolstack built from scratch to create/pause/shutdown ClickOS guests. A really
small library (~500 LoC) called `xcl` was built to easily manage MiniOS-based guests. It uses the underlying low-level userspace Xen libraries (`libxc` and `xenstore`) to interact with hypervisor and Domain-0 services.


Web / Audio Codecs
------------------

<h3 class="project">
<a href="http://jpemartins.github.io/speex.js/"><code>speex.js</code></a>
<a href="https://github.com/jpemartins/speex.js" class="github-button" data-icon="octicon-star"
  data-count-href="/jpemartins/speex.js/stargazers" data-count-api="/repos/jpemartins/speex.js#stargazers_count">Star</a>
<a href="https://github.com/jpemartins/speex.js" class="github-button" data-icon="octicon-fork"
  data-count-href="/jpemartins/speex.js/forks" data-count-api="/repos/jpemartins/speex.js#forks_count">Fork</a>
</h3>

Speex codec compiled from C to Javascript. Contains a Ogg demuxer/muxer
built from scratch, and also Microphone support to encode/decode voice data.

<h3 class="project">

<a href="http://jpemartins.github.io/amr.js/"><code>amr.js</code></a>

<a href="https://github.com/jpemartins/amr.js" class="github-button" data-icon="octicon-star"
  data-count-href="/jpemartins/amr.js/stargazers" data-count-api="/repos/jpemartins/amr.js#stargazers_count">Star</a>
</h3>

AMR Narrowband codec compiled from C to Javascript. AMR-NB is the reference 
codec in a IMS deployment.

<h3 class="project">
<a href="https://github.com/jpemartins/node-webrtc"><code>node-webrtc</code></a>
<a href="https://github.com/jpemartins/node-webrtc" class="github-button" data-icon="octicon-star"
  data-count-href="/jpemartins/node-webrtc/stargazers" data-count-api="/repos/jpemartins/node-webrtc#stargazers_count">Star</a>

</h3>

Node.JS interoperability with Google WebRTC stack.

<h3 class="project"><a href="http://code.ua.pt/projects/g711-js"><code>g711.js</code></a></h3>

G711 is a really simple codec normally supported in every VoIP application.

<h3 class="project"><a href="http://code.ua.pt/projects/rtspeech"><code>rtspeech</code></a></h3>

A demo application that examplifies all codecs I developed: it encodes/decodes a file and does a voice call to a random user, pretty much like chat roulette.

Miscellaneous
-------------

<h3 class="project">
<a href="http://jpemartins.github.io/mediacapture.js"><code>mediacapture.js</code></a>
<a href="https://github.com/jpemartins/mediacapture.js" class="github-button" data-icon="octicon-star"
  data-count-href="/jpemartins/mediacapture.js/stargazers" data-count-api="/repos/jpemartins/mediacapture.js#stargazers_count">Star</a>
</h3>

A small polyfill that implements the HTML5 Media Capture API.

<h3 class="project"><a href="https://github.com/jpemartins/usertiming.js"><code>usertiming.js</code></a></h3>

A small polyfill that implements the HTML5 User Timing API.

<h3 class="project"><a href="https://github.com/jpemartins/phonegap-websockets"><code>phonegap-websockets</code></a></h3>

A PhoneGap plugin that implements WebSockets in the browser WebView. 

<script async defer id="github-bjs" src="https://buttons.github.io/buttons.js"></script>
