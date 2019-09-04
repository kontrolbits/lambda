<template>
<q-layout view="lHh Lpr lFf">
    <q-header elevated class="grad">
        <q-toolbar>
            <q-btn flat dense round @click="leftDrawerOpen = !leftDrawerOpen" aria-label="Menu">
                <q-icon name="menu" />
            </q-btn>

            <q-toolbar-title>
                <img src="statics/icons/lambda letra 2.svg" style="width: 161px; height: 32px">
            </q-toolbar-title>

            <!-- <div>Quasar v{{ $q.version }}</div> -->
        </q-toolbar>
    </q-header>

    <q-drawer v-model="leftDrawerOpen" bordered content-class="bg-grey-10">
        <q-list>
  <div class="q-pa-md text-white meu-icone" style="max-width: 350px">
    <q-list>
      <q-expansion-item
        expand-separatorz
        icon="home"
        label="HOME"
        default-closeed
      >
          <q-list padding>
            <q-item clickable v-ripple>
              <q-item-section avatar>
                <q-icon name="inbox" />
              </q-item-section>

              <q-item-section>
                Inbox
              </q-item-section>
            </q-item>
            <q-item clickable v-ripple>
              <q-item-section avatar>
                <q-icon name="inbox" />
              </q-item-section>

              <q-item-section>
                Inbox
              </q-item-section>
            </q-item>
            <q-item clickable v-ripple>
              <q-item-section avatar>
                <q-icon name="inbox" />
              </q-item-section>

              <q-item-section>
                Inbox
              </q-item-section>
            </q-item>
        </q-list>
      </q-expansion-item>
      <q-expansion-item
        expand-separator
        icon="mail"
        label="INBOX"
        default-closeed
      >
          <q-list padding>
            <q-item clickable v-ripple>
              <q-item-section avatar>
                <q-icon name="inbox" />
              </q-item-section>

              <q-item-section>
                Inbox
              </q-item-section>
            </q-item>
            <q-item clickable v-ripple>
              <q-item-section avatar>
                <q-icon name="inbox" />
              </q-item-section>

              <q-item-section>
                Inbox
              </q-item-section>
            </q-item>
            <q-item clickable v-ripple>
              <q-item-section avatar>
                <q-icon name="inbox" />
              </q-item-section>

              <q-item-section>
                Inbox
              </q-item-section>
            </q-item>
        </q-list>
      </q-expansion-item>
      <q-expansion-item
        expand-separator
        icon="settings"
        label="CONFIGURAÇÕES"
        default-closeed
      >
          <q-list padding>
            <q-item clickable v-ripple>
              <q-item-section avatar>
                <q-icon name="inbox" />
              </q-item-section>

              <q-item-section>
                Inbox
              </q-item-section>
            </q-item>
            <q-item clickable v-ripple>
              <q-item-section avatar>
                <q-icon name="inbox" />
              </q-item-section>

              <q-item-section>
                Inbox
              </q-item-section>
            </q-item>
            <q-item clickable v-ripple>
              <q-item-section avatar>
                <q-icon name="inbox" />
              </q-item-section>

              <q-item-section>
                Inbox
              </q-item-section>
            </q-item>
        </q-list>
      </q-expansion-item>
    </q-list>
  </div>
        </q-list>
    </q-drawer>

    <q-page-container>
        <router-view />
    </q-page-container>
</q-layout>
</template>

<script>
import {
  openURL
} from 'quasar'

export default {
  name: 'MyLayout',
  data () {
    return {
      leftDrawerOpen: false
    }
  },
  methods: {
    openURL
  }
}
</script>

<style>
.grad {
    background: linear-gradient(to right, rgba(112, 54, 119, 1) 0%, rgba(241, 121, 27, 1) 100%);
}

.grad-invertido {
    background: linear-gradient(to left, rgba(112, 54, 119, 1) 0%, rgba(241, 121, 27, 1) 100%);
}
.meu-icone {
    color: rgba(241, 121, 27, 1);
}
</style>
