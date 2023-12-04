<script setup></script>

<template>
  <v-container>
    <section>
      <h2 class="text-center text-purple-accent-3">My Skills</h2>
      <p class="text-center mx-sm-5 mx-md-15">
        I mostly do UI/UX designs and also Frontend Development, however, I want to also learn more
        frameworks that could take my web applications to the next level! (Pssh... I really like
        minimalistic designs!)
      </p>
      <v-row justify="center" no-gutters>
        <v-col cols="12" sm="8" md="5" class="mx-4 my-4">
          <v-card class="h-100" variant="flat">
            <v-card-text class="d-flex flex-column ma-1">
              <div class="d-flex">
                <svg class="skill-icon" viewBox="0 0 128 128">
                  <path fill="#F0DB4F" d="M1.408 1.408h125.184v125.185H1.408z"></path>
                  <path
                    fill="#323330"
                    d="M116.347 96.736c-.917-5.711-4.641-10.508-15.672-14.981-3.832-1.761-8.104-3.022-9.377-5.926-.452-1.69-.512-2.642-.226-3.665.821-3.32 4.784-4.355 7.925-3.403 2.023.678 3.938 2.237 5.093 4.724 5.402-3.498 5.391-3.475 9.163-5.879-1.381-2.141-2.118-3.129-3.022-4.045-3.249-3.629-7.676-5.498-14.756-5.355l-3.688.477c-3.534.893-6.902 2.748-8.877 5.235-5.926 6.724-4.236 18.492 2.975 23.335 7.104 5.332 17.54 6.545 18.873 11.531 1.297 6.104-4.486 8.08-10.234 7.378-4.236-.881-6.592-3.034-9.139-6.949-4.688 2.713-4.688 2.713-9.508 5.485 1.143 2.499 2.344 3.63 4.26 5.795 9.068 9.198 31.76 8.746 35.83-5.176.165-.478 1.261-3.666.38-8.581zM69.462 58.943H57.753l-.048 30.272c0 6.438.333 12.34-.714 14.149-1.713 3.558-6.152 3.117-8.175 2.427-2.059-1.012-3.106-2.451-4.319-4.485-.333-.584-.583-1.036-.667-1.071l-9.52 5.83c1.583 3.249 3.915 6.069 6.902 7.901 4.462 2.678 10.459 3.499 16.731 2.059 4.082-1.189 7.604-3.652 9.448-7.401 2.666-4.915 2.094-10.864 2.07-17.444.06-10.735.001-21.468.001-32.237z"></path>
                </svg>
                <v-rating
                  color="purple"
                  readonly
                  half-increments
                  :model-value="1.5"
                  :item-labels="['Newbie', '', '', '', 'Pro']"
                  class="align-self-center mx-auto"></v-rating>
              </div>
              <div class="mt-4 d-flex flex-column">
                <h1>JavaScript</h1>
                <p class="mt-2">
                  I'm not too good at it, but I try...! (This is what happens when you focus too
                  much on UI/UX design...)
                </p>
              </div>
            </v-card-text>
          </v-card>
        </v-col>
        <v-col cols="12" sm="8" md="5" class="mx-4 my-4">
          <v-card class="h-100" variant="flat">
            <v-card-text class="d-flex flex-column ma-1">
              <div class="d-flex">
                <svg class="skill-icon" viewBox="0 0 128 128">
                  <path
                    fill="#1572B6"
                    d="M19.67 26l8.069 90.493 36.206 10.05 36.307-10.063L108.33 26H19.67zm69.21 50.488L86.53 98.38l.009 1.875L64 106.55v.001l-.018.015-22.719-6.225L39.726 83h11.141l.79 8.766 12.347 3.295-.004.015v-.032l12.394-3.495L77.702 77H51.795l-.222-2.355-.506-5.647L50.802 66h27.886l1.014-11H37.229l-.223-2.589-.506-6.03L36.235 43h55.597l-.267 3.334-2.685 30.154M89 14.374L81.851 6H89V1H73v4.363L81.39 13H73v5h16zm-19 0L63.193 6H70V1H55v4.363L62.733 13H55v5h15zM52 13h-8V6h8V1H38v17h14z"></path>
                </svg>
                <v-rating
                  color="purple"
                  readonly
                  half-increments
                  :model-value="2"
                  :item-labels="['Newbie', '', '', '', 'Pro']"
                  class="align-self-center mx-auto"></v-rating>
              </div>
              <div class="mt-4 d-flex flex-column">
                <h1>CSS</h1>
                <p class="mt-2">
                  Whoo boy, my favorite! I've been really trying to improve at CSS, and by far it's
                  the most enjoyable thing to do in web development!
                </p>
              </div>
            </v-card-text>
          </v-card>
        </v-col>
        <v-col cols="12" sm="8" md="5" class="mx-4 my-4">
          <v-card class="h-100" variant="flat">
            <v-card-text class="d-flex flex-column ma-1">
              <div class="d-flex">
                <svg class="skill-icon" viewBox="0 0 128 128">
                  <path
                    fill="#E44D26"
                    d="M19.569 27l8.087 89.919 36.289 9.682 36.39-9.499L108.431 27H19.569zM91.61 47.471l-.507 5.834L90.88 56H48.311l1.017 12h40.54l-.271 2.231-2.615 28.909-.192 1.69L64 106.964v-.005l-.027.012-22.777-5.916L39.65 84h11.168l.791 8.46 12.385 3.139.006-.234v.012l12.412-2.649L77.708 79H39.153l-2.734-30.836L36.152 45h55.724l-.266 2.471zM27.956 1.627h5.622v5.556h5.144V1.627h5.623v16.822h-5.623v-5.633h-5.143v5.633h-5.623V1.627zm23.782 5.579h-4.95V1.627h15.525v5.579h-4.952v11.243h-5.623V7.206zm13.039-5.579h5.862l3.607 5.911 3.603-5.911h5.865v16.822h-5.601v-8.338l-3.867 5.981h-.098l-3.87-5.981v8.338h-5.502V1.627zm21.736 0h5.624v11.262h7.907v5.561H86.513V1.627z"></path>
                </svg>
                <v-rating
                  color="purple"
                  readonly
                  half-increments
                  :model-value="2"
                  :item-labels="['Newbie', '', '', '', 'Pro']"
                  class="align-self-center mx-auto"></v-rating>
              </div>
              <div class="mt-4 d-flex flex-column">
                <h1>HTML</h1>
                <p class="mt-2">
                  This one is... boring, but I'm still trying to improve here and there!
                </p>
              </div>
            </v-card-text>
          </v-card>
        </v-col>
        <v-col cols="12" sm="8" md="5" class="mx-4 my-4">
          <v-card class="h-100" variant="flat">
            <v-card-text class="ma-1">
              <div class="d-flex">
                <svg class="skill-icon" viewBox="0 0 128 128">
                  <path
                    d="M0 8.934l49.854.158 14.167 24.47 14.432-24.47L128 8.935l-63.834 110.14zm126.98.637l-24.36.02-38.476 66.053L25.691 9.592.942 9.572l63.211 107.89zm-25.149-.008l-22.745.168-15.053 24.647L49.216 9.73l-22.794-.168 37.731 64.476zm-75.834-.17l23.002.009m-23.002-.01l23.002.01"
                    fill="none"></path>
                  <path
                    d="M25.997 9.393l23.002.009L64.035 34.36 79.018 9.404 102 9.398 64.15 75.053z"
                    fill="#35495e"></path>
                  <path
                    d="M.91 9.569l25.067-.172 38.15 65.659L101.98 9.401l25.11.026-62.966 108.06z"
                    fill="#41b883"></path>
                </svg>
                <v-rating
                  color="purple"
                  readonly
                  half-increments
                  :model-value="1"
                  :item-labels="['Newbie', '', '', '', 'Pro']"
                  class="align-self-center mx-auto"></v-rating>
              </div>
              <div class="mt-4 d-flex flex-column">
                <h1>Vue</h1>
                <p class="mt-2">
                  Oh boy, this framework has been sooo useful and helpful for me! I'm still quite a
                  beginnner at it, but I'd like to learn Vue to it's full potential!
                </p>
              </div>
            </v-card-text>
          </v-card>
        </v-col>
        <v-col cols="12" sm="8" md="5" class="mx-4 my-4">
          <v-card class="h-100" variant="flat">
            <v-card-text class="ma-1">
              <div class="d-flex">
                <svg class="skill-icon" viewBox="0 0 128 128">
                  <path d="M64.004 0H34.102l29.902 61.848" fill="#1697F6"></path>
                  <path
                    d="M64.004 80v48L0 18.664h33.527L64.004 80zm0-80h29.898L64.004 61.848"
                    fill="#7BC6FF"></path>
                  <path d="M94.473 18.664H128L64.004 128V80l30.469-61.336z" fill="#AEDDFF"></path>
                </svg>
                <v-rating
                  color="purple"
                  readonly
                  half-increments
                  :model-value="1.5"
                  :item-labels="['Newbie', '', '', '', 'Pro']"
                  class="align-self-center mx-auto"></v-rating>
              </div>
              <div class="mt-4 d-flex flex-column">
                <h1>Vuetify</h1>
                <p class="mt-2">
                  Vuetify is AMAZING! This bad boy here has helped me reduce so much stress on UI/UX
                  Designs! (It's what's keeping me going on the Front end development path!)
                </p>
              </div>
            </v-card-text>
          </v-card>
        </v-col>
        <v-col cols="12" sm="8" md="5" class="mx-4 my-4">
          <v-card class="h-100" variant="flat">
            <v-card-text class="ma-1">
              <div class="d-flex">
                <svg class="skill-icon" viewBox="0 0 128 128">
                  <g fill="#FFFFFF">
                    <path
                      fill-rule="evenodd"
                      clip-rule="evenodd"
                      d="M64 5.103c-33.347 0-60.388 27.035-60.388 60.388 0 26.682 17.303 49.317 41.297 57.303 3.017.56 4.125-1.31 4.125-2.905 0-1.44-.056-6.197-.082-11.243-16.8 3.653-20.345-7.125-20.345-7.125-2.747-6.98-6.705-8.836-6.705-8.836-5.48-3.748.413-3.67.413-3.67 6.063.425 9.257 6.223 9.257 6.223 5.386 9.23 14.127 6.562 17.573 5.02.542-3.903 2.107-6.568 3.834-8.076-13.413-1.525-27.514-6.704-27.514-29.843 0-6.593 2.36-11.98 6.223-16.21-.628-1.52-2.695-7.662.584-15.98 0 0 5.07-1.623 16.61 6.19C53.7 35 58.867 34.327 64 34.304c5.13.023 10.3.694 15.127 2.033 11.526-7.813 16.59-6.19 16.59-6.19 3.287 8.317 1.22 14.46.593 15.98 3.872 4.23 6.215 9.617 6.215 16.21 0 23.194-14.127 28.3-27.574 29.796 2.167 1.874 4.097 5.55 4.097 11.183 0 8.08-.07 14.583-.07 16.572 0 1.607 1.088 3.49 4.148 2.897 23.98-7.994 41.263-30.622 41.263-57.294C124.388 32.14 97.35 5.104 64 5.104z"></path>
                    <path
                      d="M26.484 91.806c-.133.3-.605.39-1.035.185-.44-.196-.685-.605-.543-.906.13-.31.603-.395 1.04-.188.44.197.69.61.537.91zm2.446 2.729c-.287.267-.85.143-1.232-.28-.396-.42-.47-.983-.177-1.254.298-.266.844-.14 1.24.28.394.426.472.984.17 1.255zM31.312 98.012c-.37.258-.976.017-1.35-.52-.37-.538-.37-1.183.01-1.44.373-.258.97-.025 1.35.507.368.545.368 1.19-.01 1.452zm3.261 3.361c-.33.365-1.036.267-1.552-.23-.527-.487-.674-1.18-.343-1.544.336-.366 1.045-.264 1.564.23.527.486.686 1.18.333 1.543zm4.5 1.951c-.147.473-.825.688-1.51.486-.683-.207-1.13-.76-.99-1.238.14-.477.823-.7 1.512-.485.683.206 1.13.756.988 1.237zm4.943.361c.017.498-.563.91-1.28.92-.723.017-1.308-.387-1.315-.877 0-.503.568-.91 1.29-.924.717-.013 1.306.387 1.306.88zm4.598-.782c.086.485-.413.984-1.126 1.117-.7.13-1.35-.172-1.44-.653-.086-.498.422-.997 1.122-1.126.714-.123 1.354.17 1.444.663zm0 0"></path>
                  </g>
                </svg>
                <v-rating
                  color="purple"
                  readonly
                  half-increments
                  :model-value="0.5"
                  :item-labels="['Newbie', '', '', '', 'Pro']"
                  class="align-self-center mx-auto"></v-rating>
              </div>
              <div class="mt-4 d-flex flex-column">
                <h1>Github</h1>
                <p class="mt-2">
                  Github is pretty cool! I still am learning bits and pieces of it as I go along my
                  journey!
                </p>
              </div>
            </v-card-text>
          </v-card>
        </v-col>
      </v-row>
    </section>
  </v-container>
</template>

<style scoped>
.skill-icon {
  width: 60px;
  height: 60px;
}
</style>
