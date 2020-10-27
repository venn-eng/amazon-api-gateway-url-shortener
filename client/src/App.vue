<!-- Copyright 2019 Amazon.com, Inc. or its affiliates. All Rights Reserved.
SPDX-License-Identifier: MIT-0

Permission is hereby granted, free of charge, to any person obtaining a copy of this
software and associated documentation files (the "Software"), to deal in the Software
without restriction, including without limitation the rights to use, copy, modify,
merge, publish, distribute, sublicense, and/or sell copies of the Software, and to
permit persons to whom the Software is furnished to do so.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED,
INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A
PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT
HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION
OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE
SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE. -->

<template>
  <div id="app">
    <section class="section">
      <nav
        class="navbar is-fixed-top is-dark"
        role="navigation"
        aria-label="main navigation"
      >
        <div class="navbar-brand">
          <div class="navbar-item">
            <svg height="40" width="135" viewBox="0 0 665 215" shape-rendering="geometricPrecision" class="sc-pzYib hNHnjO"><defs><clipPath id="clip-path"><rect class="venn-logo-1" x="423.81" y="170.44" width="234.2" height="42.04"></rect></clipPath></defs><polygon class="venn-logo-2" points="56.47 1 0 1 28.32 50.06 84.79 50.06 56.47 1"></polygon><polygon class="venn-logo-2" points="204.75 50.06 233.07 1 176.6 1 148.28 50.06 204.75 50.06"></polygon><polygon class="venn-logo-3" points="148.28 50.06 176.6 1 56.47 1 84.79 50.06 148.28 50.06"></polygon><polygon class="venn-logo-2" points="144.77 153.94 116.53 105.04 88.3 153.94 116.53 203 144.77 153.94"></polygon><polygon class="venn-logo-3" points="116.53 105.04 84.79 50.06 28.32 50.06 88.3 153.94 116.53 105.04"></polygon><polygon class="venn-logo-3" points="116.53 105.04 144.77 153.94 204.75 50.06 148.28 50.06 116.53 105.04"></polygon><polygon class="venn-logo-4" points="84.79 50.06 116.53 105.04 148.28 50.06 84.79 50.06"></polygon><path class="venn-logo-5" d="M340.65,50.11,295.71,154.63h-4.66l-45-104.52h4.14a2.26,2.26,0,0,1,1.69.64,3.19,3.19,0,0,1,.85,1.27l38.8,90.42a25.15,25.15,0,0,1,1.06,3c.28,1,.53,2,.74,3,.28-1,.56-2,.85-3a22.09,22.09,0,0,1,1.06-3L334.08,52a4.16,4.16,0,0,1,1.06-1.38,2.44,2.44,0,0,1,1.59-.53Z"></path><path class="venn-logo-5" d="M436,141.8A25.81,25.81,0,0,1,430,147a47.07,47.07,0,0,1-8.74,4.51,65.21,65.21,0,0,1-10.71,3.18,57.26,57.26,0,0,1-11.82,1.22,47.94,47.94,0,0,1-19.34-3.77,40.46,40.46,0,0,1-14.74-10.86,49.38,49.38,0,0,1-9.38-17.44A77.8,77.8,0,0,1,352,100.25a66.78,66.78,0,0,1,3.12-20.94,47.62,47.62,0,0,1,9.07-16.37,40.48,40.48,0,0,1,14.52-10.71,47.58,47.58,0,0,1,19.5-3.82,42,42,0,0,1,15.85,3,36.53,36.53,0,0,1,12.88,8.75,40.91,40.91,0,0,1,8.64,14.25,56,56,0,0,1,3.13,19.4c0,1.49-.64,2.23-1.91,2.23H357.61c-.07.7-.1,1.39-.1,2.06v2.18a74.29,74.29,0,0,0,3,22,45.75,45.75,0,0,0,8.37,16,35.19,35.19,0,0,0,13.09,9.81,42.65,42.65,0,0,0,17.12,3.34,50.41,50.41,0,0,0,14.52-1.86,56.33,56.33,0,0,0,10.28-4.08,41.23,41.23,0,0,0,6.42-4.08q2.28-1.86,2.91-1.86a1.72,1.72,0,0,1,1.38.64Zm-2.33-49.5a48.37,48.37,0,0,0-2.71-16.8A36.51,36.51,0,0,0,423.49,63a31.22,31.22,0,0,0-11.18-7.74,36.64,36.64,0,0,0-14-2.65,42.82,42.82,0,0,0-15.95,2.81,34.8,34.8,0,0,0-12.14,8A40.42,40.42,0,0,0,362,76a56.77,56.77,0,0,0-4.08,16.33Z"></path><path class="venn-logo-5" d="M470.08,70.36a57.26,57.26,0,0,1,17.44-16,42.85,42.85,0,0,1,22.1-5.94,39.38,39.38,0,0,1,15.21,2.71,28.14,28.14,0,0,1,10.81,7.73,33.55,33.55,0,0,1,6.47,12.35,58.4,58.4,0,0,1,2.17,16.54v66.89h-5.62V87.74a54.61,54.61,0,0,0-1.8-14.63,29,29,0,0,0-5.57-11,24.49,24.49,0,0,0-9.38-6.89,33.72,33.72,0,0,0-13.25-2.38,39.47,39.47,0,0,0-21.14,6,59.94,59.94,0,0,0-17.23,16.59v79.19h-5.62V50.11h2.65a1.94,1.94,0,0,1,2.12,2.12Z"></path><path class="venn-logo-5" d="M582.23,70.36a57.11,57.11,0,0,1,17.43-16,42.91,42.91,0,0,1,22.1-5.94A39.31,39.31,0,0,1,637,51.12a28.17,28.17,0,0,1,10.82,7.73,33.54,33.54,0,0,1,6.46,12.35,58,58,0,0,1,2.18,16.54v66.89h-5.62V87.74A54.61,54.61,0,0,0,649,73.11a29.16,29.16,0,0,0-5.57-11,24.56,24.56,0,0,0-9.38-6.89,33.75,33.75,0,0,0-13.25-2.38,39.53,39.53,0,0,0-21.15,6,59.91,59.91,0,0,0-17.22,16.59v79.19h-5.62V50.11h2.65a1.94,1.94,0,0,1,2.12,2.12Z"></path><polygon class="venn-logo-5" points="483.98 184.16 476.71 184.16 476.71 180.94 494.86 180.94 494.86 184.16 487.59 184.16 487.59 201.98 483.98 201.98 483.98 184.16"></polygon><polygon class="venn-logo-5" points="498.26 180.94 502.07 180.94 506.91 196.9 506.97 196.9 511.54 180.94 514.9 180.94 519.44 196.9 519.5 196.9 524.37 180.94 528.15 180.94 521.51 201.98 517.64 201.98 513.22 186.56 513.16 186.56 508.74 201.98 504.87 201.98 498.26 180.94"></polygon><g class="venn-logo-6"><path class="venn-logo-5" d="M540.25,199.21c4,0,7.06-2.94,7.06-7.87,0-4.75-3.06-7.66-7.06-7.66s-7.06,2.91-7.06,7.66c0,4.93,3.1,7.87,7.06,7.87m0-18.63A10.3,10.3,0,0,1,551,191.34c0,6.67-4.63,11-10.73,11s-10.75-4.33-10.75-11,4.65-10.76,10.75-10.76"></path><polygon class="venn-logo-5" points="581.87 180.94 585.48 180.94 585.48 192.28 585.48 201.98 581.87 201.98 581.87 190.22 581.87 180.94"></polygon><path class="venn-logo-5" d="M601,180.58a12.82,12.82,0,0,1,7.45,2.38,28.09,28.09,0,0,1-2.16,2.35,9.41,9.41,0,0,0-5.2-1.6c-4.32,0-7.18,3.12-7.18,7.57,0,4.84,2.68,7.93,7.18,7.93a8.73,8.73,0,0,0,4.21-1v-5H600v-2.67h8.62v9.52a13.17,13.17,0,0,1-7.63,2.29c-6.58,0-10.79-4.45-10.79-11.06,0-6.19,4.27-10.7,10.79-10.7"></path><polygon class="venn-logo-5" points="613.72 180.94 617.35 180.94 624.29 190.83 631.23 180.94 634.84 180.94 634.84 201.98 631.35 201.98 631.35 186.29 624.26 196.21 617.17 186.29 617.17 201.98 613.72 201.98 613.72 180.94"></polygon><path class="venn-logo-5" d="M644.67,194.53h6.85l-3.4-9.8h-.06ZM646,180.94h4.24L658,202h-3.88l-1.59-4.54h-8.86L642.12,202h-3.91Z"></path><path class="venn-logo-5" d="M563.22,197.44a12,12,0,0,0,6,1.71c2.76,0,4.15-1.2,4.15-2.88,0-4.75-11.84-1.62-11.84-9.65,0-3.36,2.79-6,7.51-6a15.58,15.58,0,0,1,7.72,1.94l-2.36,2.41a12.14,12.14,0,0,0-5.24-1.16c-2.43,0-3.88,1.23-3.88,2.79,0,4.72,11.84,1.51,11.84,9.68,0,3.45-2.61,6.1-7.9,6.1a16,16,0,0,1-8.43-2.47Z"></path><rect class="venn-logo-7" x="429.96" y="176.6" width="29.72" height="29.72" transform="translate(-5.07 370.69) rotate(-45.01)"></rect><path class="venn-logo-5" d="M433.74,197.42c-.16-6.73,7.94-5.85,7.94-9.3,0-1.12-.89-2.08-2.84-2.08a5.76,5.76,0,0,0-3.79,1.63l-1.49-1.49a8.11,8.11,0,0,1,5.38-2.18c3.37,0,5.08,1.87,5.08,4.08,0,5.08-7.87,4.18-7.87,8.42h7.75v2H433.76Z"></path><path class="venn-logo-5" d="M459.87,187.49h-8.6a6.21,6.21,0,0,0-6.15,6.52,4.42,4.42,0,0,0,4.63,4.76,6.21,6.21,0,0,0,6.18-6.51,5,5,0,0,0-.87-3h3ZM450,196.91c-1.55,0-2.47-1-2.47-2.92,0-2.45,1.63-4.65,3.59-4.65,1.53,0,2.45,1,2.45,2.94,0,2.45-1.61,4.63-3.57,4.63"></path></g><text class="venn-logo-8" transform="translate(381.71 201.98)">by</text></svg>
          </div>
          <div class="navbar-item">
            <h1 class="title has-text-white">Links</h1>
          </div>
          <a
            role="button"
            class="navbar-burger burger"
            aria-label="menu"
            aria-expanded="false"
            data-target="navbarCollapse"
            v-bind:class="{ 'is-active': isOpen }"
            @click="isOpen = !isOpen"
          >
            <span aria-hidden="true"></span>
            <span aria-hidden="true"></span>
            <span aria-hidden="true"></span>
          </a>
        </div>

        <div
          id="navbarCollapse"
          class="navbar-menu"
          v-bind:class="{ 'is-active': isOpen }"
        >
          <div class="navbar-start">
            <!-- <router-link class="navbar-item" to="/">Dashboard</router-link> -->
          </div>

          <div class="navbar-end">
            <a
              class="navbar-item"
              v-if="authorized"
              v-on:click="logout()"
              v-bind:href="logOutUrl"
              >Log Out</a
            >
            <a class="navbar-item" v-if="!authorized" v-bind:href="logInUrl"
              >Log In</a
            >
          </div>
        </div>
      </nav>
    </section>
    <section class="section">
      <div class="container">
        <div v-if="!authorized" style="text-align: center;">
          <img src="/simba.png" style="border-radius:100%;">
        </div>
        <div v-if="authorized">
          <router-view />
        </div>
        <div v-else>
          <p v-if="linkNotFound">
            We're sorry, that link could not be found.
          </p>
        </div>
      </div>
    </section>
  </div>
</template>

<script>
import { mapState } from "vuex";
import axios from "axios";

// Set Cognito Vars
const clientId = process.env.VUE_APP_CLIENT_ID;
const authDomain = process.env.VUE_APP_AUTH_DOMAIN;
const queryStringParams = new URLSearchParams(window.location.search);
const cognitoCode = queryStringParams.get("code") || null;
const lnf = queryStringParams.get("lnf") || null;
const redUrl = window.location.origin;

export default {
  name: "app",
  data() {
    return {
      appName: `Vennly`,
      signUpUrl: `${authDomain}/signup?response_type=code&client_id=${clientId}&redirect_uri=${redUrl}`,
      logInUrl: `${authDomain}/login?response_type=code&client_id=${clientId}&redirect_uri=${redUrl}`,
      logOutUrl: `${authDomain}/logout?client_id=${clientId}&logout_uri=${redUrl}`,
      linkNotFound: lnf,
      isOpen: false,
    };
  },
  created() {
    if (cognitoCode) this.exchangeToken();
    else this.exchangeRefreshToken();
  },
  methods: {
    convertJSON: function (json) {
      const oAuthTokenBodyArray = Object.entries(json).map(([key, value]) => {
        const encodedKey = encodeURIComponent(key);
        const encodedValue = encodeURIComponent(value);
        return `${encodedKey}=${encodedValue}`;
      });
      return oAuthTokenBodyArray.join("&");
    },
    exchangeRefreshToken: function () {
      const oauthTokenBodyJson = {
        grant_type: "refresh_token",
        client_id: clientId,
        refresh_token: localStorage.getItem("cognitoRefreshToken"),
      };
      const oauthTokenBody = this.convertJSON(oauthTokenBodyJson);

      if (oauthTokenBodyJson.refresh_token) {
        return axios
          .post(`${authDomain}/oauth2/token`, oauthTokenBody, {
            ["Content-Type"]: "application/x-www-form-urlencoded",
          })
          .then((response) => {
            let json = response.data;
            if (json.id_token) {
              localStorage.setItem("cognitoIdentityToken", json.id_token);
              this.$store.commit("authorize");
            }
          })
          .catch(() => {
            this.$store.commit("deAuthorize");
          });
      } else {
        return new Promise((res) => {
          return res({});
        });
      }
    },
    exchangeToken: function () {
      const oauthTokenBodyJson = {
        grant_type: "authorization_code",
        client_id: clientId,
        code: cognitoCode,
        redirect_uri: redUrl,
      };
      const oauthTokenBody = this.convertJSON(oauthTokenBodyJson);

      return axios
        .post(`${authDomain}/oauth2/token`, oauthTokenBody, {
          ["Content-Type"]: "application/x-www-form-urlencoded",
        })
        .then((response) => {
          let json = response.data;
          if (json.id_token) {
            localStorage.setItem("cognitoIdentityToken", json.id_token);
            localStorage.setItem("cognitoRefreshToken", json.refresh_token);
            this.$store.commit("authorize");
          }
          let query = Object.assign({}, this.$route.query);
          delete query.code;
          this.$router.replace({ query });
        })
        .catch(() => {
          this.$store.commit("deAuthorize");
        });
    },
    logout: function () {
      localStorage.setItem("cognitoIdentityToken", null);
      localStorage.setItem("cognitoRefreshToken", null);
    },
  },
  computed: {
    ...mapState(["authorized"]),
  },
};
</script>
