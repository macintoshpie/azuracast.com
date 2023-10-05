---
# https://vitepress.dev/reference/default-theme-home-page
layout: home

hero:
  name: "AzuraCast"
  text: "Simple, Self-Hosted Web Radio"
  tagline: "A free and open-source web radio station in a box"
  image:
    src: /img/logo.svg
    alt: AzuraCast Logo
  actions:
    - theme: brand
      text: Get Started
      link: /markdown-examples
    - theme: alt
      text: Live Demo
      link: /api-examples

features:
  - title: Everything's Included
    icon: 
      src: '/img/icons/box2-heart-fill.svg'
    details: AzuraCast installs everything you need to get a web radio station up and running in minutes.
  - title: Powerful and Intuitive
    icon:
      src: '/img/icons/person-hearts.svg'
    details: Manage every aspect of your radio station via a simple yet powerful web interface.
  - title: Run Anywhere with Docker
    icon:
      src: '/img/icons/rocket-takeoff-fill.svg'
    details: Install AzuraCast onto any server (or desktop) that supports Docker.
---

<section class="showcase">
      <div class="row">
        <div class="showcase-img" style="background-image: url('img/bg-showcase-1.png');"></div>
        <div class="showcase-text">
          <h2>Web-Based Station Management</h2>
          <p class="lead mb-0">
            Upload media, manage playlists, create local mount points and remote relays, view analytics and reports and much more, all
            from the convenience of your web browser.
          </p>
        </div>
      </div>
      <div class="row">
        <div class="showcase-img" style="background-image: url('img/bg-showcase-2.png');"></div>
        <div class="showcase-text">
          <h2 class="title">Multi-Station Administration</h2>
          <p class="lead mb-0">
            Host multiple stations on a single installation, create new user accounts and unique roles with granular permissions.
            Back up your installation and keep track of every station from one central location.
          </p>
        </div>
      </div>
      <div class="row">
        <div class="showcase-img" style="background-image: url('img/bg-showcase-3.png');">
        </div>
        <div class="showcase-text">
          <article class="box">
            <h2>Built-in Public Pages</h2>
            <p>
              Out of the box, each station includes a public-facing player page that can also be embedded into your own web site.
              Our powerful APIs let you build your own players and interfaces that take advantage of our rich metadata support.
            </p>
          </article>
        </div>
      </div>
  </section>

<style lang="scss" scoped>
.showcase {
  h2 {
    line-height: 24px;
    font-size: 20px;
    font-weight: 600;
    margin-bottom: 5px;
  }

  p {
    line-height: 24px;
    font-size: 15px;
    font-weight: 500;
    color: var(--vp-c-text-2);
  }

    .row {
        display: flex;

        &:nth-child(2) {
            .showcase-text {
                order: 1;
            }
            .showcase-img {
                order: 2;
            }
        }
    }

    .showcase-text {
        width: 65%;
        padding: 3rem;
    }

    .showcase-img {
        width: 35%;
        min-height: 10rem;
        background-size: cover;
    }

    @media (min-width: 768px) {
        .showcase-text {
            padding: 7rem;
        }
    }
}
</style>
