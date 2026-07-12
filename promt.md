I have created a website using only HTML and CSS. You will also use only HTML and CSS. Do not change anything. Just create these sections. Keep the design consistent with my website's theme and color palette.

Create a **Why Attend** section.

Then create an **Event Schedule** section.

Then create a **Get Direction To The Event Hall** section. It should include the address, a small contact form, and a Google Map on the right side.

Do not generate the complete code for the website. Just provide these sections only. Keep the HTML and CSS separate. The HTML should be inside a separate `<section>` tag, and the CSS should also be provided separately.


<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="./style.css">
    <title>Devconf-2026</title>
</head>

<body>
    <!-- this is navber section -->
    <nav>
        <section class="nav-child">
            <div class="nav-child-logo">
                <img src="./assets/logo-mini.png" width="40px" height="40px" alt="">
                <h3>DEVCONF <br> 2026</h3>
            </div>
            <div class="nav-child-direction">
                <li><a href="#">Speakers</a></li>
                <li><a href="#">Schedul</a></li>
                <li><a href="#">Tracks</a></li>
                <li><a href="#">Venue</a></li>
                <li><a href="#">Blog</a></li>
            </div>
            <div>
                <Button class="button">Register Now</Button>
            </div>
        </section>
    </nav>

    <!-- this is hero section -->
    <section class="hero-section">
        <div class="hero-section-text">
            <h1>Code. Connect. Create</h1>
            <div class="hero-section-text-p">
                <p>Join 4,000+ engineers, founders, and builders at the premier developer conference of 2026. Three days
                    of cutting-edge talks, hands-on workshops and meaningful connections.</p>
            </div>
        </div>
        <button class="button">
            Register Now
        </button>
    </section>
    <!-- this is job card presentation section -->
    <section class="job-card-section">
        <div class="job-card-section-float">
            <h1>
                Meet the Speakers
            </h1>

            <div class="job-card-grid">
                <div class="job-grid-card">
                    <img src="./assets/andrej.png" alt="">
                    <div>
                        <h4>AI / ML</h4>
                        <h1>Andrej Karpathy</h1>
                        <p>Pretraining team, Anthropic</p>
                    </div>
                </div>
                <div class="job-grid-card">
                    <img src="./assets/demis.png" alt="">
                    <div>
                        <h4>Cloud & DevOps</h4>
                        <h1>Demis Hassabis</h1>
                        <p>Co-Founder and CEO, Google DeepMind</p>
                    </div>
                </div>
                <div class="job-grid-card">
                    <img src="./assets/gary.png" alt="">
                    <div>
                        <h4>Frontend</h4>
                        <h1>Gary Marcus</h1>
                        <p>Staff Engineer, Vercel</p>
                    </div>
                </div>
                <div class="job-grid-card">
                    <img src="./assets/mustafa.png" alt="">
                    <div>
                        <h4>Security</h4>
                        <h1>Mustafa Suleyman</h1>
                        <p>CEO of Microsoft AI</p>
                    </div>
                </div>
            </div>
        </div>
    </section>
    <!-- this is pricing section -->
    <section class="pricing">
        <div class="pricing-child">
            <div class="pcheading">
                <h1>Secure Your Spot</h1>
                <p>Early-bird pricing ends August 15, 2026.</p>
            </div>

            <div class="card-area">
                <div class="pricing-card pcstandard">
                    <section>
                        <h5>STANDARD</h5>
                        <h1>$399</h1>
                        <p>per person</p>
                    </section>
                    <hr>
                    <div>
                        <li>Access to all 3 conference days</li>
                        <li>48 curated technical talks</li>
                        <li>2 workshop sessions</li>
                        <li>Networking lunch & coffee breaks</li>
                        <li>Conference swag bag</li>
                        <li>Digital recordings (30 days)</li>
                    </div>
                    <footer class="pcbutton">
                        <button>Get Standard</button>
                    </footer>
                </div>
                <div class="pricing-card pcpro">
                    <section>
                        <h5>PRO</h5>
                        <h1>$749</h1>
                        <p>per person</p>
                    </section>
                    <hr>
                    <div>
                        <li>Everything in Standard</li>
                        <li>Unlimited workshop access</li>
                        <li>Speaker meet & greet</li>
                        <li>VIP networking dinner</li>
                        <li>Lifetime recording access</li>
                        <li>1-on-1 mentorship (30 min)</li>
                    </div>
                    <footer class="pcbutton">
                        <button>Get Pro</button>
                    </footer>
                </div>
                <div class="pricing-card pcteam">
                    <section>
                        <h5>TEAM</h5>
                        <h1>$5,999</h1>
                        <p>per person</p>
                    </section>
                    <hr>
                    <div class="licolor">
                        <li>Everything in Pro (10 seats)</li>
                        <li>Dedicated team lounge access</li>
                        <li>Private workshop booking</li>
                        <li>Company logo on event page</li>
                        <li>Recruitment booth (1 day)</li>
                        <li>Priority customer support</li>
                    </div>
                    <footer class="pcbutton">
                        <button>Contact Us</button>
                    </footer>
                </div>
            </div>
        </div>
    </section>

    <!-- this is ai generated section -->
     <section class="aigen">

     </section>
</body>

</html>

* {
    font-family: system-ui, -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Oxygen, Ubuntu, Cantarell, 'Open Sans', 'Helvetica Neue', sans-serif;
}

body {
    display: flex;
    flex-direction: column;
    align-items: center;
}
/* nav sectin css file */
.button {
    width: 192px;
    height: 56px;
    padding: 4px;
    color: white;
    border-radius: 12px;
    font-size: large;
    background-color: #1D4ED8;
    border-color: #3B82F6;
    cursor: pointer;
}

nav {
    width: 1551px;
    display: flex;
    align-items: center;
    justify-content: center;
}

.nav-child {
    width: 1320px;
    display: flex;
    align-items: center;
    justify-content: space-between;
    height: 50px;
    padding: 10px;
}

.nav-child-logo {
    display: flex;
    align-items: center;
    justify-content: center;
    gap: 5px;
}

.nav-child-direction {
    display: flex;
    flex-direction: row;
    list-style: none;
    gap: 24px;

    li a {
        text-decoration: none;
        color: black;
    }
}

/* hero section css  */

.hero-section {
    display: flex;
    flex-direction: column;
    align-items: center;
    justify-content: space-around;
    width: 1551px;
    height: 786px;
    background-image: url(./assets/banner.jpg);
    background-repeat: no-repeat;
    background-size: cover;
    background-position: center;
}

.hero-section-text {
    color: white;
    display: flex;
    flex-direction: column;
    align-items: center;

    h1 {
        font-size: 60px;
    }

    div {
        width: 500px;

        p {
            text-align: center;
        }
    }
}

/* this is job card section  css sheet */

.job-card-section {
    width: 1551px;
    height: 1322px;
    display: flex;
    align-items: center;
    justify-content: center;
}

.job-card-section-float {
    display: flex;
    flex-direction: column;
    align-items: center;
    justify-content: center;
    width: 1440px;
    height: 1279px;
    gap: 40px;

}

.job-card-grid {
    display: grid;
    grid-template-columns: 1fr 1fr;
    row-gap: 32px;
    column-gap: 32px;
}

.job-grid-card {
    border: 1px solid rgb(221, 221, 221);
    border-radius: 12px;

    img {
        border-radius: 12px 12px 0px 0px;
    }

    div {
        padding: 24px;
    }

    h4 {
        color: #3B82F6;
    }

    p {
        color: rgb(131, 131, 131);
    }
}

/* this is pricing card section css */

.pricing {
    display: flex;
    align-items: center;
    justify-content: center;
    margin-bottom: 40px;

}

.pcheading{
    margin-bottom: 30px;
}

.card-area {
    width: 1160px;
    height: 444px;
    display: grid;
    grid-template-columns: auto auto auto;
    gap: 24px;
}

.pricing-child {
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: center;
}

.pricing-card {
    padding: 20px;
    border: 1px solid rgb(160, 160, 160);
    border-radius: 12px;

    div {
        padding-left: 20px;
    }

    li::marker {
        color: #83b9f8;
    }
}

.pcstandard {
    h1{
        color: black;
    }
    color: rgb(105, 105, 105);
    .pcbutton {
        margin-top: 30px;
        text-align: center;

        button {
            width: 304px;
            height: 45px;
            border-radius: 8px;
            padding: 11px;
            background-color: white;
            border: #3B82F6 solid 1px;
            color: #2563EB;
        }
    }
}

.pcpro {
    background-color: #0D1B2A;

    h5 {
        color: #93C5FD;
    }

    h1 {
        color: white;
    }

    color: rgb(145, 145, 145);

    .pcbutton {
        margin-top: 30px;
        text-align: center;

        button {
            width: 304px;
            height: 45px;
            border-radius: 8px;
            padding: 11px;
            background-color: #3463e3;
            color: white;
            border: none;
        }
    }

}

.pcteam {
    h1{
        color: black;
    }
    color: rgb(105, 105, 105);
    background-color: rgb(243, 243, 243);

    .pcbutton {
        margin-top: 30px;
        text-align: center;

        button {
            width: 304px;
            height: 45px;
            border-radius: 8px;
            padding: 11px;
        }
    }
}

/* this is ai generated css section */