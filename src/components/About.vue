<template>
  <section id="about">
    <b-container>
      <b-heading class="text-center mb-4">A propos</b-heading>
      <b-row>
        <b-col md="6">
          <p
            class="text-justify"
          >Lorem ipsum dolor sit amet consectetur adipisicing elit. Ducimus beatae ratione, sunt dolor laudantium magni autem! Atque sit quos ex, hic magni fugit, voluptatem minima in perspiciatis explicabo harum assumenda! Lorem ipsum dolor sit amet consectetur adipisicing elit. Voluptatem magni iure, ipsum provident ullam autem dolor pariatur impedit labore inventore consequatur quos numquam dicta maiores est nobis possimus nesciunt doloribus! Lorem ipsum, dolor sit amet consectetur adipisicing elit. Neque deserunt amet aliquid eligendi doloribus cumque iusto porro iure? Id officiis magni a aperiam fuga obcaecati ipsum dolores expedita debitis nisi. Lorem ipsum dolor sit amet consectetur adipisicing elit.</p>

          <div class="mt-2">
            <b-heading>Nos coordonnées</b-heading>
            <address>
              <b-row>
                <b-col>
                  <ul class="list-unstyled">
                    <li class="mb-2">
                      <unicon name="map-pin"></unicon>
                      <p class="d-inline-flex mb-0 ml-2">69 Rue banane</p>
                    </li>
                    <li class="mb-2">
                      <unicon name="phone"></unicon>
                      <a class="ml-1" href="tel:+491570156">+49 157 0156</a>
                    </li>
                  </ul>
                </b-col>
                <b-col>
                  <ul class="list-unstyled">
                    <li class="mb-2">
                      <unicon name="facebook"></unicon>
                      <a class="ml-1" href="https://facebook.com/x">@x</a>
                    </li>
                    <li class="mb-2">
                      <unicon name="instagram"></unicon>
                      <a class="ml-1" href="https://instagram.com/x">@x</a>
                    </li>
                  </ul>
                </b-col>
              </b-row>
            </address>
          </div>
        </b-col>
        <b-col md="6">
          <b-row>
            <b-col>
              <b-heading class="mt-n1">Visitez nous</b-heading>
              <div>
                <b-img blank blank-color="rgba(128, 255, 255, 0.5)" width="560" height="256" fluid></b-img>
              </div>
            </b-col>
          </b-row>
          <b-row class="mt-2 mb-2">
            <b-col>
              <b-img blank blank-color="rgba(128, 255, 255, 0.5)" width="256" height="256" fluid></b-img>
            </b-col>
            <b-col>
              <b-img blank blank-color="rgba(128, 255, 255, 0.5)" width="256" height="256" fluid></b-img>
            </b-col>
            <b-col>
              <b-img blank blank-color="rgba(128, 255, 255, 0.5)" width="256" height="256" fluid></b-img>
            </b-col>
          </b-row>
        </b-col>
      </b-row>
    </b-container>
  </section>
</template>

<script>
import BHeading from "./BHeading.vue";
export default {
  components: {
    BHeading
  }
};
</script>

<style lang="scss" scoped>
</style>
