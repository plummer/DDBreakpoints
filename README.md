	  ____         _         _  _    _           
	 |  _ \   ___ | |  ___  (_)| |_ | |_  ___    
	 | | | | / _ \| | / _ \ | || __|| __|/ _ \   
	 | |_| ||  __/| || (_) || || |_ | |_|  __/ _ 
	 |____/  \___||_| \___/ |_| \__| \__|\___|(_)
	  ____   _         _  _          _           
	 |  _ \ (_)  __ _ (_)| |_  __ _ | |          
	 | | | || | / _` || || __|/ _` || |          
	 | |_| || || (_| || || |_| (_| || |          
	 |____/ |_| \__, ||_| \__|\__,_||_|          
	            |___/                            

#DDBreakpoints Overview

This repo is home to our Breakpoints tool, which is made up of an SCSS Mixin and some JavaScript. We use this tool to accelerate our development process when creating responsive websites and webapps - it also helps us simplify consistency accross all of our projects.

We were inspired to create DDBreakpoints back in May 2013, as a result of Chris Coyier's CSS-Tricks article: [Naming Media Queries](http://css-tricks.com/naming-media-queries/).

As we built more responsive websites, our philosophy for creating responsive sites that don't look responsive (i.e. don't use a predictable standard grid) meant that we needed to add more and more breakpoints. While we always took a mobile-first approach, we would regularly find ourselves adding an "and-below" breakpoint for edge cases. This meant that our breakpoints mixin was getting overly large and repetitively complex.

Today, DDBreakpoints is used on almost every responsive project by Deloitte Digital in Australia... and now, it's available for your projects as well!

#Getting Started

We believe that clearly-written and well-commented code, beats extensive documentation. If you're interested in reading a little more about this library and trying out some examples, please visit our [repo page](https://deloittedigital.github.io/DDBreakpoints).

#Who is [Deloitte Digital](http://www.deloittedigital.com) anyway?

**Part Business. Part Creative. Part Technology. One hundred per cent digital.**

Pioneered in Australia, Deloitte Digital is committed to helping clients unlock the business value of emerging technologies. We provide clients with a full suite of digital services, covering digital strategy, user experience, content, creative, engineering and implementation across mobile, web and social media channels.

#LICENSE (BSD-3-Clause)
Copyright (C) 2015, Deloitte Digital. All rights reserved.

DDBreakpoints can be downloaded from: https://github.com/DeloitteDigital/DDBreakpoints

Redistribution and use in source and binary forms, with or without
modification, are permitted provided that the following conditions are met:

* Redistributions of source code must retain the above copyright notice, this
list of conditions and the following disclaimer.

* Redistributions in binary form must reproduce the above copyright notice,
this list of conditions and the following disclaimer in the documentation
and/or other materials provided with the distribution.

* Neither the name of the copyright holder nor the names of its contributors 
may be used to endorse or promote products derived from this software without 
specific prior written permission.

THIS SOFTWARE IS PROVIDED BY THE COPYRIGHT HOLDERS AND CONTRIBUTORS "AS IS"
AND ANY EXPRESS OR IMPLIED WARRANTIES, INCLUDING, BUT NOT LIMITED TO, THE
IMPLIED WARRANTIES OF MERCHANTABILITY AND FITNESS FOR A PARTICULAR PURPOSE ARE
DISCLAIMED. IN NO EVENT SHALL THE COPYRIGHT HOLDER OR CONTRIBUTORS BE LIABLE
FOR ANY DIRECT, INDIRECT, INCIDENTAL, SPECIAL, EXEMPLARY, OR CONSEQUENTIAL
DAMAGES (INCLUDING, BUT NOT LIMITED TO, PROCUREMENT OF SUBSTITUTE GOODS OR
SERVICES; LOSS OF USE, DATA, OR PROFITS; OR BUSINESS INTERRUPTION) HOWEVER
CAUSED AND ON ANY THEORY OF LIABILITY, WHETHER IN CONTRACT, STRICT LIABILITY,
OR TORT (INCLUDING NEGLIGENCE OR OTHERWISE) ARISING IN ANY WAY OUT OF THE USE
OF THIS SOFTWARE, EVEN IF ADVISED OF THE POSSIBILITY OF SUCH DAMAGE.
