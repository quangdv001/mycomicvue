<template>
    <b-container class="bv-example-row mt-3">
      <b-row>
        <b-col>
          <template>
            <b-breadcrumb :items="items" class="bg-white"></b-breadcrumb>
          </template>
        </b-col>
      </b-row>
    </b-container>
</template>

<script>
    export default {
      data() {
        return {
          items: [
            {
              text: 'Admin',
              href: '#'
            },
            {
              text: 'Manage',
              href: '#'
            },
            {
              text: 'Library',
              active: true
            }
          ]
        }
      }
    }
</script>