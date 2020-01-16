<template>
  <div id="container">
    <section>
      <h2>What You Expect</h2>

      <div class="mb-16">
        <p>I am using the same dialog instance. Only the container that house the modal is different.</p>
        <a href="https://github.com/fuxingloh/medium-modal-article" target="_blank">You can check it out on GitHub.</a>
      </div>

      <article>
        <div class="flex-center">
          <div>
            <art class="wh-48px"/>
          </div>
          <h3 class="ml-16">Content Title</h3>
        </div>

        <p class="mt-16">Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut
          labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud
          exercitation ullamco laboris nisi ut
          aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in
          voluptate velit esse cillum dolore
          eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt
          in culpa qui officia deserunt
          mollit anim id est laborum.</p>

        <div class="mt-16 flex-end">
          <button class="primary" @click="active = true">Click Me</button>
        </div>

        <modal-dialog v-if="active === true" @close="active = false"/>
      </article>
    </section>

    <section>
      <h2>Nested Positions</h2>

      <article>
        <div class="flex-center">
          <div>
            <art class="wh-48px"/>
          </div>
          <h3 class="ml-16">Content Title</h3>
        </div>

        <p class="mt-16">Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut
          labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud
          exercitation ullamco laboris nisi ut
          aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in
          voluptate velit esse cillum dolore
          eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt
          in culpa qui officia deserunt
          mollit anim id est laborum.</p>

        <div class="mt-16 flex-end">
          <button class="primary" @click="active = true">Click Me</button>
        </div>

        <div class="relative">
          <modal-dialog v-if="active === true" @close="active = false"/>
        </div>
      </article>
    </section>

    <section>
      <h2>Z-Index</h2>

      <article>
        <div class="flex-center">
          <div class="relative index-3">
            <art class="wh-48px index-3"/>
          </div>
          <h3 class="ml-16">Content Title</h3>
        </div>

        <p class="mt-16">Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut
          labore et dolore magna <span class="relative index-3 primary">aliqua</span>. Ut enim ad minim veniam, quis
          nostrud exercitation ullamco <span class="relative index-3 primary">laboris</span> nisi ut
          aliquip ex ea commodo consequat. Duis aute irure dolor in <span
            class="relative index-3 primary">reprehenderit</span> in voluptate velit esse cillum dolore
          eu fugiat nulla pariatur. <span class="relative index-3 primary">Excepteur</span> sint occaecat cupidatat non
          proident, sunt in culpa qui officia deserunt
          mollit anim id est laborum.</p>

        <div class="mt-16 flex-end">
          <button class="primary" @click="active = true">Click Me</button>
        </div>

        <modal-dialog v-if="active === true" @close="active = false"/>
      </article>
    </section>

    <section>
      <h2>Cascading CSS</h2>

      <article class="Cascading">
        <div class="flex-center">
          <div>
            <art class="wh-48px"/>
          </div>
          <h3 class="ml-16">Content Title</h3>
        </div>

        <p class="mt-16">Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut
          labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud
          exercitation ullamco laboris nisi ut
          aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in
          voluptate velit esse cillum dolore
          eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt
          in culpa qui officia deserunt
          mollit anim id est laborum.</p>

        <div class="mt-16 flex-end">
          <button class="primary" @click="active = true">Click Me</button>
        </div>

        <modal-dialog v-if="active === true" @close="active = false"/>
      </article>
    </section>

    <section>
      <h2>Scrolling</h2>

      <h5 class="mb-16">Scroll Me!</h5>

      <article class="Scrolling">
        <div class="flex-center">
          <div>
            <art class="wh-48px"/>
          </div>
          <h3 class="ml-16">Content Title</h3>
        </div>

        <p class="mt-16">Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut
          labore et dolore magna aliqua.</p>

        <div class="mt-16 flex-end">
          <button class="primary" @click="active = true">Click Me</button>
        </div>

        <p class="mt-16">Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut
          labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud
          exercitation ullamco laboris nisi ut
          aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in
          voluptate velit esse cillum dolore
          eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt
          in culpa qui officia deserunt
          mollit anim id est laborum.</p>

        <p class="mt-16">Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut
          labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud
          exercitation ullamco laboris nisi ut
          aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in
          voluptate velit esse cillum dolore
          eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt
          in culpa qui officia deserunt
          mollit anim id est laborum.</p>

        <p class="mt-16">Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut
          labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud
          exercitation ullamco laboris nisi ut
          aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in
          voluptate velit esse cillum dolore
          eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt
          in culpa qui officia deserunt
          mollit anim id est laborum.</p>

        <modal-dialog v-if="active === true" @close="active = false"/>
      </article>
    </section>

    <section>
      <h2>iOS Full Screen 100vh</h2>

      <article>
        <div class="mb-24 p-16-24 bg-steam border-3">
          You need to experience this on iOS.
        </div>


        <div class="mt-16 flex-end">
          <button class="primary" @click="iOS = true">Click Me</button>
        </div>
      </article>
    </section>

    <div class="iOS fixed position-0" v-if="iOS">
      <div class="flex-column wh-100 bg-white">
        <div class="p-24 hr-bot">
          <button class="primary w-100" @click="iOS = false">Fixed Close Button</button>
        </div>
        <div class="flex-grow p-24">
          <div class="flex-center">
            <div>
              <art class="wh-48px"/>
            </div>
            <h3 class="ml-16">Content Title</h3>
          </div>

          <p class="mtb-24">Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut
            labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud
            exercitation ullamco laboris nisi ut
            aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in
            voluptate velit esse cillum dolore
            eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt
            in culpa qui officia deserunt
            mollit anim id est laborum.</p>
        </div>
        <div class="p-24 hr-top">
          <button class="primary w-100" @click="iOS = false">Fixed Close Button</button>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
  import Art from "../components/Logo";
  import ModalDialog from "../components/ModalDialog";

  export default {
    components: {ModalDialog, Art},
    data() {
      return {
        active: false,
        iOS: false
      }
    }
  }
</script>

<style lang="less">
  #container {
    padding: 24px;
  }

  section {
    margin: 48px auto;
    max-width: 768px;

    h2 {
      margin-bottom: 16px;
    }
  }

  article {
    padding: 24px;
    border: 1px solid #EFEFEF;

    position: relative;
  }

  .Scrolling {
    max-height: 300px;
    overflow-y: scroll;
  }

  .Cascading {
    font-size: 24px;
  }

  .iOS {
    height: 100vh;
  }
</style>
