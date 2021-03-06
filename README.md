# bootstrap-photo-gallery

A simple jQuery plugin that will create a Bootstrap based Photo Gallery for your images. Supports variable height for the images and captions. An optional "modal" box with "next" and "previous" paging is also included. Plugin requires Bootstrap (3.3.5 and above) jQuery (1.10 and above). 

![alt tag](http://michaelsoriano.com/wp-content/uploads/2013/11/bootstrap-gallery-demo.gif)

###How to Use:

Make sure you include the required files before the plugin. 

You need to create an unordered list of your images. 

```
 <ul class="first">
    <li>
        <img  src="images/photodune-174908-rocking-the-night-away-xs.jpg">
    </li>
    <li>
        <img  src="images/photodune-287182-blah-blah-blah-yellow-road-sign-xs.jpg">
    </li>
    <li>
        <img  src="images/photodune-460760-colors-xs.jpg">
    </li>
    ...
</ul>

```

Then initialize the plugin and pass in the Boostrap classes for different sizes as a parameter. The "hasModal" is true by default - but can be turned off by setting it to "false". 

```
$('ul.first').bsPhotoGallery({
    "classes" : "col-lg-2 col-md-4 col-sm-3 col-xs-4 col-xxs-12",
    "hasModal" : true
  });
```

The original tutorial can be found here: 

"How to create a responsive photo gallery using Bootstrap" :
http://michaelsoriano.com/create-a-responsive-photo-gallery-with-bootstrap-framework/

and

"Let’s Add Next and Previous Buttons to our Bootstrap Photo Gallery"
http://michaelsoriano.com/next-and-previous-buttons-bootstrap-photo-gallery/

THIS SOFTWARE IS PROVIDED "AS IS" AND ANY EXPRESSED OR IMPLIED WARRANTIES, INCLUDING, BUT NOT LIMITED TO, THE IMPLIED WARRANTIES OF MERCHANTABILITY AND FITNESS FOR A PARTICULAR PURPOSE ARE DISCLAIMED. IN NO EVENT SHALL THE REGENTS OR CONTRIBUTORS BE LIABLE FOR ANY DIRECT, INDIRECT, INCIDENTAL, SPECIAL, EXEMPLARY, OR CONSEQUENTIAL DAMAGES (INCLUDING, BUT NOT LIMITED TO, PROCUREMENT OF SUBSTITUTE GOODS OR SERVICES; LOSS OF USE, DATA, OR PROFITS; OR BUSINESS INTERRUPTION)
HOWEVER CAUSED AND ON ANY THEORY OF LIABILITY, WHETHER IN CONTRACT, STRICT LIABILITY, OR TORT (INCLUDING NEGLIGENCE OR OTHERWISE) ARISING IN ANY WAY OUT OF THE USE OF THIS SOFTWARE, EVEN IF ADVISED OF THE POSSIBILITY OF SUCH DAMAGE.
