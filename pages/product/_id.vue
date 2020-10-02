<template>
  <div id="sup">
    <b-container>
      <b-row class="justify-content-md-center">
        <b-card
          class="card text-dark bg-info "
          :title="this.$route.params.id.title"
          :img-src="this.$route.params.id.image_url"
          :img-alt="url"
          img-top
          tag="article"
          style="max-width: 30rem;"
        >
          <b-card-text>
            Synopsis : {{ this.$route.params.id.synopsis }}
            <br>
            Score : {{ this.$route.params.id.score }}
            <br>
            Episodes :  {{ this.$route.params.id.episodes }}
            <br>
            Rated : {{ this.$route.params.id.rated }}
            <br>
            Image : {{ this.$route.params.id.image_url }}
            <br>
            Type : {{ this.$route.params.id.type }}
            <br>
            Start Date : {{ this.$route.params.id.start_date }}
            <br>
            End Date : {{ this.$route.params.id.end_date }}
            <br>
            Airing : {{ this.$route.params.id.airing }}
            <br>
            Members : {{ this.$route.params.id.members }}
            <br>
            Members : {{ this.$route.params.id.members }}
          </b-card-text>
        </b-card>
      </b-row>
    </b-container>
  </div>
</template>
