# announcements-events



## Tutorial		  
For detailed instruction's, view Solodev's [How to Style Announcements and Events Sections](https://www.solodev.com/blog/web-design/how-to-style-announcements-and-events-sections.stml) article.
 
## Demo
  		  
Try out a working example on [JSFiddle](https://jsfiddle.net/solodev/a0ropafg/).

## HTML

The tutorial contains the following basic HTML markup.

```
<section class="two-column-list mb-sm-5 pr-lg-3 container-fluid" id="two-column-list">
    <div class="container">
        <div class="row">
            <div class="col-lg-6 pr-0">
                <section aria-label="Announcements" class="announcements">
                    <h2 class="font-weight-bold border-bottom pb-3 mt-3 mb-0 pr-5">Announcements</h2>

                    <div class="announcement-slider border-r-xs-0 border-r position-relative">
                        <div>
                            <ul class="nolist list-unstyled position-relative mb-0 px-lg-5 pt-lg-5">
                                <li class="border-bottom pb-3 mt-3">
                                    <span class="meta text-uppercase">April 02nd, 2018</span>
                                    <h3 class="font-weight-bold mt-0">
                                        <a href="https://www.solodev.com/news/solodev-ranked-as-high-performer-on-g2-crowds-spring-2018-web-content-management-grid.stml">
                                            Solodev Ranked as High Performer on G2 Crowd
                                        </a>
                                    </h3>
                                    <p class="m-0 post_intro">Florida's premier web content management software company ranked favorably in user-based G2 Crowd ratings.</p>
                                </li>
                                <li class="border-bottom pb-3 mt-3">

                                    <span class="meta text-uppercase">January 30th, 2018</span>


                                    <h3 class="font-weight-bold mt-0">
                                        <a href="https://www.solodev.com/news/solodev-earns-highest-ranking-software-tool-for-state-of-florida-in-nationwide-g2-crowd-study.stml">
Solodev Earns “Highest Ranking Software Tool”
                                        </a>
                                    </h3>
                                    <p class="m-0 post_intro">In a national survey, users ranked Solodev as among the best software tools in the country.</p>
                                </li>
                                <li class="border-bottom pb-3 mt-3">
                                    <span class="meta text-uppercase">January 18th, 2018</span>
                                    <h3 class="font-weight-bold mt-0">
                                        <a href="https://www.solodev.com/news/city-of-miami-beach-launches-enticing-website-to-match-vibrant-city.stml">
                                            City of Miami Beach Launches Enticing Website
                                        </a>
                                    </h3>

                                    <p class="m-0 post_intro">The iconic tourist destination looked to become the golden standard for other city websites throughout the United States.</p>
                                </li>
                            </ul>
                            <a class="all pos-stat text-uppercase ml-lg-5" href="https://www.solodev.com/news/">All announcements
                                <i class="fa fa-caret-right" aria-hidden="true"></i>
                            </a>
                            <div class="left-right-arrows pr-lg-5">
                                <button class="prev-arrow-announcement" type="button"><i class="fa fa-chevron-left"></i></button>
                                <button class="next-arrow-announcement" type="button"><i class="fa fa-chevron-right"></i></button>
                            </div>
                        </div>

                        <div>
                            <ul class="nolist list-unstyled position-relative mb-0 px-lg-5 pt-lg-5">
                                <li class="border-bottom pb-3 mt-3">
                                    <span class="meta text-uppercase">05/10/2019</span>

                                    <h3 class="font-weight-bold mt-0">
                                        <a href="https://www.solodev.com/news/solodev-earns-national-recognition-as-marketing-and-commerce-cms-leader.stml">
                                            Solodev Earns National Recognition as Marketing and Commerce CMS Leader
                                        </a>
                                    </h3>
                                    <p class="m-0 post_intro">Solodev has achieved rigorous Marketing & Commerce competency in recent listing from Amazon Web Services.</p>
                                </li>
                                <li class="border-bottom pb-3 mt-3">
                                    <span class="meta text-uppercase">05/10/2019</span>

                                    <h3 class="font-weight-bold mt-0">
                                        <a href="https://www.solodev.com/news/solodev-helps-power-american-dairy-association-north-easts-online-passions.stml">
                                            Solodev Helps Power American Dairy Association North East's Online Passions
                                        </a>
                                    </h3>

                                    <p class="m-0 post_intro">The newly redesigned website combines three legacy organizations into one user-optimized website for the AWS Cloud.</p>
                                </li>
                                <li class="border-bottom pb-3 mt-3">
                                    <span class="meta text-uppercase">05/10/2019</span>
                                    <h3 class="font-weight-bold mt-0">
                                        <a href="http://www.marketwired.com/press-release/solodev-recognized-as-number-one-high-performer-on-g2-crowds-summer-2017-web-content-2225641.htm">
                                            Solodev Recognized as Number One 
                                        </a>
                                    </h3>
                                    <p class="m-0 post_intro">Web experience platform provider ranked among global content management software companies based largely on user ratings</p>
                                </li>
                            </ul>
                            <a class="all pos-stat text-uppercase" href="/announcements/">All announcements
                                <i class="fa fa-caret-right" aria-hidden="true"></i>
                            </a>
                            <div class="left-right-arrows pr-lg-5">
                                <button class="prev-arrow-announcement" type="button"><i class="fa fa-chevron-left"></i></button>
                                <button class="next-arrow-announcement" type="button"><i class="fa fa-chevron-right"></i></button>
                            </div>
                        </div>
                    </div>
                </section>
            </div>
            <div class="col-lg-6 pl-0">
                <section class="events-section pl-lg-3" aria-label="Events">
                    <h2 class="font-weight-bold border-bottom pb-3 mt-3 pl-lg-5 mb-0">Events</h2>
                    <div class="events p-lg-5">
                        <div class="events-block">
                            <ul class="nolist list-unstyled position-relative mb-0 px-lg-3">
                                <li class="border-bottom d-flex align-items-center">
                                    <div class="events-date text-uppercase text-center">
                                        <a class="text-white" href="#">May
                                            <span>10</span>
                                        </a>
                                    </div>
                                    <div class="d-inline-block pl-3 event-li">
                                        <h3 class="font-weight-bold mt-0">
                                            <a href="#">
                                                CMS City Exhibition
                                            </a>
                                        </h3>
                                        <p>
                                            10:30 PM
                                        </p>
                                    </div>
                                </li>
                                <li class="border-bottom d-flex align-items-center">
                                    <div class="events-date text-uppercase text-center">
                                        <a class="text-white" href="#">May
                                            <span>31</span>
                                        </a>
                                    </div>
                                    <div class="d-inline-block pl-3 event-li">
                                        <h3 class="font-weight-bold mt-0">
                                            <a href="#">
                                                Content Management Expo
                                            </a>
                                        </h3>
                                        <p>
                                            6:30 PM
                                        </p>
                                    </div>
                                </li>
                                <li class="border-bottom d-flex align-items-center">
                                    <div class="events-date text-uppercase text-center">
                                        <a class="text-white" href="#">June
                                            <span>07</span>
                                        </a>
                                    </div>
                                    <div class="d-inline-block pl-3 event-li">
                                        <h3 class="font-weight-bold mt-0">
                                            <a href="#">
                                                Techolocon
                                            </a>
                                        </h3>
                                        <p>
                                            8:30 AM
                                        </p>
                                    </div>
                                </li>
                            </ul>
                            <a class="all pos-stat text-uppercase ml-lg-5" href="/calendar/">All events
                                <i class="fa fa-caret-right" aria-hidden="true"></i>
                            </a>
                            <div class="left-right-arrows second">
                                <button class="prev-arrow-events" type="button"><i class="fa fa-chevron-left"></i></button>
                                <button class="next-arrow-events" type="button"><i class="fa fa-chevron-right"></i></button>
                            </div>

                        </div>
                        <div class="events-block">
                            <ul class="nolist list-unstyled position-relative mb-0 px-lg-3">

                                <li class="border-bottom d-flex align-items-center">
                                    <div class="events-date text-uppercase text-center">
                                        <a class="text-white" href="#">June
                                            <span>15</span>
                                        </a>
                                    </div>
                                    <div class="d-inline-block pl-3 event-li">
                                        <h3 class="font-weight-bold mt-0">
                                            <a href="#">
                                                Cloud City Expo
                                            </a>
                                        </h3>
                                        <p>
                                            12PM
                                        </p>
                                    </div>
                                </li>
                                <li class="border-bottom d-flex align-items-center">
                                    <div class="events-date text-uppercase text-center">
                                        <a class="text-white" href="#">June
                                            <span>23</span>
                                        </a>
                                    </div>
                                    <div class="d-inline-block pl-3 event-li">
                                        <h3 class="font-weight-bold mt-0">
                                            <a href="#">
                                                Solodev at the Education Conference
                                            </a>
                                        </h3>
                                        <p>
                                            10:30
                                        </p>
                                    </div>
                                </li>
                                <li class="border-bottom d-flex align-items-center">
                                    <div class="events-date text-uppercase text-center">
                                        <a class="text-white" href="#">July
                                            <span>25</span>
                                        </a>
                                    </div>
                                    <div class="d-inline-block pl-3 event-li">
                                        <h3 class="font-weight-bold mt-0">
                                            <a href="#">
                                                AWS Challenge Conference
                                            </a>
                                        </h3>
                                        <p>
                                            9:15AM
                                        </p>
                                    </div>
                                </li>
                            </ul>
                            <a class="all text-uppercase ml-lg-5" href="/calendar/">All events
                                <i class="fa fa-caret-right" aria-hidden="true"></i>
                            </a>
                            <div class="left-right-arrows second">
                                <button class="prev-arrow-events" type="button"><i class="fa fa-chevron-left"></i></button>
                                <button class="next-arrow-events" type="button"><i class="fa fa-chevron-right"></i></button>
                            </div>
                        </div>
                    </div>
                </section>
            </div>
        </div>
    </div>
</section>
```

## CSS

All required CSS is contained with announcements-events.css

## JS

All required CSS is contained with announcements-events.js

## External Resources

This tutorial includes the following third party resources.

```
<link href="https://maxcdn.bootstrapcdn.com/bootstrap/4.0.0-alpha.6/css/bootstrap.min.css" rel="stylesheet">
<link href="https://cdnjs.cloudflare.com/ajax/libs/slick-carousel/1.8.1/slick.min.css" rel="stylesheet">

<script src="https://code.jquery.com/jquery-3.2.1.min.js"></script>
<script src="https://cdnjs.cloudflare.com/ajax/libs/tether/1.4.0/js/tether.min.js"></script>
<script src="https://maxcdn.bootstrapcdn.com/bootstrap/4.0.0-alpha.6/js/bootstrap.min.js"></script>
<script src="https://cdnjs.cloudflare.com/ajax/libs/slick-carousel/1.8.1/slick.min.js"></script>

```

