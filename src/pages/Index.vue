<template>
  <q-page class="flex bg-secondary">
    <!-- Carousel -->
    <div class="full-width shadow-4">
      <q-carousel
        animated
        arrows
        infinite
        :autoplay="15000"
        v-model="slideImages"
        transition-prev="slide-right"
        transition-next="slide-left"
        height="800px"
      >
        <q-carousel-slide
          name="first"
          img-src="https://cdn.quasar.dev/img/mountains.jpg"
        >
          <div class="custom-caption flex-center-content">
            <div>
              <div class="carousel-text-header mb-2">
                WITAJ NA STRONIE GRUPY RIDERS
              </div>
              <div class="carousel-text">
                Jako Grupa już od wielu lat sprawiamy, że wydarzenia stają się
                wyjątkowe, niezależnie czy jest to wesele, impreza klubowa czy
                plenerowa.
              </div>
              <div class="carousel-text-buttons mt-3">
                <span class="mr-1">
                  <q-btn
                    push
                    size="lg"
                    color="accent"
                    label="Zobacz terminarz"
                  />
                </span>
                <span class="ml-1">
                  <q-btn
                    push
                    size="lg"
                    color="accent"
                    label="Skontaktuj się z nami"
                  />
                </span>
              </div>
            </div>
          </div>
        </q-carousel-slide>
        <q-carousel-slide
          name="second"
          img-src="https://cdn.quasar.dev/img/parallax1.jpg"
        >
          <div class="custom-caption flex-center-content">
            <div class="carousel-text">
              Dzięki bardzo bogatemu i zróżnicowanemu repertuarowi oraz
              odpowiedniemu zapleczu technicznemu nasza grupa potrafi zapewnić
              profesjonalną oprawę muzyczną, włącznie z kompletnym nagłośnieniem
              oraz oświetleniem, praktycznie każdej imprezy, od wesel, poprzez
              dancingi, bale, imprezy klubowe, zabawy, aż po imprezy plenerowe.
            </div>
          </div>
        </q-carousel-slide>
        <q-carousel-slide
          name="third"
          img-src="https://cdn.quasar.dev/img/parallax2.jpg"
        >
          <div class="custom-caption flex-center-content">
            <div>
              <div class="carousel-text">
                Zapraszamy do wysłuchania naszego demo, oraz zapoznania się z
                pełnym materiałem informacyjnym zamieszczonym na tej stronie,
                dzięki któremu poznasz nas bliżej, zorientujesz się co i jak
                gramy, a także jak prezentujemy się podczas wybranych typów
                imprez.
              </div>
              <div class="carousel-text-buttons mt-3">
                <q-btn push size="lg" color="accent" label="Posłuchaj" />
              </div>
            </div>
          </div>
        </q-carousel-slide>
      </q-carousel>
    </div>

    <!-- Demo -->
    <div class="full-width">
      <div class="row p-2 pb-0">
        <div class="col-7 p-1">
          <div class="text-primary text-h3 mb-2">
            Demo
          </div>
          <q-separator class="separator mb-2" />
          <div class="text-primary text-body1 text-justify mb-2">
            Tutaj moszesz posłuchać jak gramy. Demo stanowi pewien przekrój
            przez nasz repertuar i zawiera jednocześnie hity na imprezy klubowe,
            kawałki w stylu rockowym, jak również utwory typowo weselne.
          </div>
          <div class="text-primary text-body1 text-justify mb-2">
            Zaprszamy do wysłuchania :)
          </div>
        </div>
        <div class="col-5 p-1">
          <q-carousel
            animated
            navigation
            transition-prev="slide-right"
            transition-next="slide-left"
            v-model="slideVideo"
            class="shadow-2"
          >
            <q-carousel-slide name="soft-jazz">
              <q-video
                class="absolute-full"
                src="https://www.youtube.com/embed/k3_tw44QsZQ"
              />
            </q-carousel-slide>

            <q-carousel-slide name="Rihanna">
              <q-video
                class="absolute-full"
                src="https://www.youtube.com/embed/kOkQ4T5WO9E"
              />
            </q-carousel-slide>

            <q-carousel-slide name="chill-mix">
              <q-video
                class="absolute-full"
                src="https://www.youtube.com/embed/rQLhZlI6aTM"
              />
            </q-carousel-slide>
          </q-carousel>
        </div>
      </div>
    </div>

    <!-- Imprezy -->
    <div class="full-width">
      <img
        class="relative-position"
        style="transform: translateY(6px)"
        src="../assets/page-decorator-up.svg"
      />
    </div>
    <div class="full-width bg-primary">
      <div class="row p-2 pt-1 flex-center-content">
        <div class="text-secondary text-h3">
          Imprezy
        </div>
      </div>
      <div class="row p-2 pb-0">
        <div class="col-12 p-2">
          <q-card class="bg-light-accent text-justify">
            <img
              style="height: 200px"
              src="https://cdn.quasar.dev/img/mountains.jpg"
            />
            <q-card-section>
              <div class="text-h5 text-primary p-1 pb-0 flex-center-content">
                Wesela
              </div>
            </q-card-section>
            <q-card-section>
              <div class="text-body1 text-primary p-2 pb-0">
                Wesele jest szczególnym wydarzeniem w życiu, a my, jako zespół,
                staramy się, aby było mile wspominane.
              </div>
              <div class="text-body1 text-primary p-2 pb-0">
                Para Młoda oraz Goście weselni mogą z naszej strony liczyć na
                kompleksową oprawę muzyczną tej wyjątkowej dla nich nocy. Od
                tradyjnego marsza na "wejście" i przywitania Pary Młodej i
                wszystkich Gości, poprzez zaśpiewanie "Sto lat!" Młodej Parze,
                zaproszenie ich do tradycyjnego pierwszego tańca, aż po mające
                miejsce o północy oczepiny, podczas których zorganizujemy zabawy
                dla Pary Młodej oraz chętnych Gości, kończąc na podziękowaniu
                dla Rodziców Pary Młodej - gramy, śpiewamy i zabawiamy gości!
              </div>
              <div class="text-body1 text-primary p-2 pb-0">
                W prowadzeniu wesel posiadamy bardzo duże doświadczenie,
                nabywane przez nas stopniowo przez wiele lat. Różnorodność i
                uniwersalność naszego repertuaru, w powiązaniu z umiejętnością
                dostosowywania utworów do nastrojów gości gwarantuje zawsze
                dobrą zabawę.
              </div>
              <div class="text-body1 text-primary p-2 pb-0">
                Podczas wesela utrzymujemy bezpośredni kontakt z gośćmi.
                Zejdziemy także do nich ze sceny, aby wspólnie z wszystkimi
                zaśpiewać przyśpiewki weselne, akompaniując przy tym na
                akordeonie oraz gitarze.
              </div>
              <div class="text-body1 text-primary p-2 pb-0">
                Jesteśmy otwarci na wszelkie sugestie ze strony Pary Młodej. W
                szczególnych momentach uroczystości, takich jak np. "pierwszy
                taniec", "podziękowanie dla Rodziców", zagramy utwory wybrane
                przez nich. Nie stanowi dla nas także problemu opracowanie na
                ich specjalne życzenie utworu, który chcieliby usłyszeć, a
                którego nie posiadamy aktualnie w repertuarze.
              </div>
              <div class="text-body1 text-primary p-2">
                Na zakończenie słów kilka... Jako zespół pragniemy jednak
                szczerze przestrzec Parę Młodą przed często zbyt dosłownie
                pojmowanym "uzgadnianiem repertuaru" i pochopnie tworzeniem
                przez nich listy utworów, które my, jako zespół, mielibyśmy
                zagrać. Zdobywając przez lata doświadczenie zdążyliśmy się
                przekonać, że takie praktyki nie są dobre, dlatego nie
                realizujemy wesel w ten sposób.
              </div>
            </q-card-section>
          </q-card>
        </div>
        <div class="col-6 p-2">
          <q-card class="bg-light-accent text-justify">
            <img
              style="height: 200px"
              src="https://cdn.quasar.dev/img/mountains.jpg"
            />
            <q-card-section>
              <div class="text-h5 text-primary p-1 pb-0 flex-center-content">
                Imprezy klubowe i zabawy
              </div>
            </q-card-section>
            <q-card-section>
              <div class="text-body1 text-primary p-2 pb-0">
                Imprezy z nami to jazda na maxa! Zagramy najnowsze hity z list
                przebojów, a także wcześniejsze sprawdzone hiciory z poprzednich
                lat. Mamy też kilka własnych utworów.
              </div>
              <div class="text-body1 text-primary p-2">
                Odpowiednio nagłośnimy salę,aby każdy usłyszał i poczuł bit!
                Dzięki rozbudowanemu systemowi oświetlenia scenicznego, w
                połaczeniu z wytwornicą dymu, zapewnimy super imprezowy klimat
                na sali.
              </div>
              <div class="carousel-text-buttons">
                <q-btn
                  push
                  size="lg"
                  color="accent"
                  class="full-width"
                  label="Zobacz nasze instrumentarium i zaplecze"
                />
              </div>
            </q-card-section>
          </q-card>
        </div>
        <div class="col-6">
          <div class="col-6 p-2">
            <q-card class="bg-light-accent text-justify">
              <div class="text-h5 text-primary p-1 pb-0 flex-center-content">
                Imprezy okolicznościowe
              </div>
              <q-card-section>
                <div class="text-body1 text-primary p-2">
                  Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed
                  do eiusmod tempor incididunt ut labore et dolore magna aliqua.
                  Ut enim ad minim veniam, quis nostrud exercitation ullamco
                  laboris nisi ut aliquip ex ea commodo consequat.
                </div>
              </q-card-section>
            </q-card>
          </div>
          <div class="col-6 p-2">
            <q-card class="bg-light-accent text-justify">
              <div class="text-h5 text-primary p-1 pb-0 flex-center-content">
                Imprezy plenerowe
              </div>
              <q-card-section>
                <div class="text-body1 text-primary p-2">
                  Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed
                  do eiusmod tempor incididunt ut labore et dolore magna aliqua.
                  Ut enim ad minim veniam, quis nostrud exercitation ullamco
                  laboris nisi ut aliquip ex ea commodo consequat.
                </div>
              </q-card-section>
            </q-card>
          </div>
        </div>
      </div>
    </div>
    <div class="full-width">
      <img
        class="relative-position"
        style="transform: translateY(-5px)"
        src="../assets/page-decorator-down.svg"
      />
    </div>

    <!-- Galeria -->
    <div class="full-width">
      <div class="row p-2 pt-0 pb-0">
        <div class="col-12 p-2">
          <div class="text-primary text-h3 mb-2">
            Galeria
          </div>
          <q-separator class="separator mb-2" />
        </div>
      </div>
      <div class="row p-2 pt-0 full-width">
        <div class="col-12 p-2 pt-0">
          <q-carousel
            swipeable
            animated
            v-model="slideGallery"
            thumbnails
            infinite
            height="800px"
            class="shadow-2"
          >
            <q-carousel-slide
              :name="1"
              img-src="https://cdn.quasar.dev/img/mountains.jpg"
            />
            <q-carousel-slide
              :name="2"
              img-src="https://cdn.quasar.dev/img/parallax1.jpg"
            />
            <q-carousel-slide
              :name="3"
              img-src="https://cdn.quasar.dev/img/parallax2.jpg"
            />
            <q-carousel-slide
              :name="4"
              img-src="https://cdn.quasar.dev/img/quasar.jpg"
            />
          </q-carousel>
        </div>
      </div>
    </div>

    <!-- Instrumentarium i zaplecze -->
    <div class="full-width bg-light-accent shadow-2">
      <div class="text-primary text-h3 p-2 flex-center-content">
        Instrumentarium i zaplecze
      </div>
      <q-carousel
        v-model="slideInstruments"
        transition-prev="scale"
        transition-next="scale"
        infinite
        swipeable
        animated
        control-color="white"
        navigation
        padding
        arrows
        height="700px"
        class="bg-light-accent text-white"
      >
        <q-carousel-slide name="main" class="column no-wrap flex-center">
          <div class="row p-2 flex-center-content">
            <div class="text-primary text-h4">
              Instrumenty
            </div>
          </div>
          <div class="row p-2 pt-0">
            <div class="col-3 p-2">
              <q-card>
                <img src="../assets/instruments/005-balalaika.svg" />
                <div
                  class="text-h5 text-primary p-1 flex-center-content text-center"
                >
                  Elektryczna gitara solowa
                </div>
              </q-card>
            </div>
            <div class="col-3 p-2">
              <q-card>
                <img src="../assets/instruments/018-electric-guitar.svg" />
                <div
                  class="text-h5 text-primary p-1 flex-center-content text-center"
                >
                  Elektryczna gitara basowa
                </div>
              </q-card>
            </div>
            <div class="col-3 p-2">
              <q-card>
                <img src="../assets/instruments/012-keyboard.svg" />
                <div
                  class="text-h5 text-primary p-1 flex-center-content text-center"
                >
                  Klawisz
                  <br /><br />
                </div>
              </q-card>
            </div>
            <div class="col-3 p-2">
              <q-card>
                <img src="../assets/instruments/014-drum.svg" />
                <div
                  class="text-h5 text-primary p-1 flex-center-content text-center"
                >
                  Perkusja
                  <br /><br />
                </div>
              </q-card>
            </div>
          </div>
        </q-carousel-slide>
        <q-carousel-slide name="optional" class="column no-wrap flex-center">
          <div class="row p-2 pt-0 flex-center-content">
            <div class="text-primary text-h4">
              Opcjonalnie
            </div>
          </div>
          <div class="row p-2 pt-0 flex-center-content">
            <div class="col-4 p-2">
              <q-card>
                <img src="../assets/instruments/003-acoustic-guitar.svg" />
                <div
                  class="text-h5 text-primary p-1 flex-center-content text-center"
                >
                  Gitara akustyczna
                  <br /><br />
                </div>
              </q-card>
            </div>
            <div class="col-4 p-2">
              <q-card>
                <img src="../assets/instruments/001-accordion.svg" />
                <div
                  class="text-h5 text-primary p-1 flex-center-content text-center"
                >
                  Akordeon
                  <br /><br />
                </div>
              </q-card>
            </div>
          </div>
        </q-carousel-slide>
        <q-carousel-slide name="sound" class="column no-wrap flex-center">
          <div class="row p-2 pt-0 flex-center-content">
            <div class="text-primary text-h4">
              Nagłośnienie
            </div>
          </div>
          <div class="row p-2 pt-0 flex-center-content">
            <div class="col-10 p-2">
              <q-card>
                <div class="row p-1 pb-0">
                  <div class="col-2">
                    <img
                      style="width: 100%"
                      src="../assets/instruments/028-speaker.svg"
                    />
                  </div>
                  <div class="col-10 flex-center-content">
                    <div
                      class="text-h6 text-primary p-1 flex-center-content text-justify"
                    >
                      Nagłośnienie, którym dysponujemy, jest zrealizowane jako
                      system dwupasmowy, w skład którego wchodzą: 4 kolumny typu
                      "nadstawka" i 4 kolumny typu "odwrotka", wraz z
                      odpowiednim napędem.
                    </div>
                  </div>
                </div>
                <div class="row p-1">
                  <div class="col-10 flex-center-content">
                    <div
                      class="text-h6 text-primary p-1 flex-center-content text-justify"
                    >
                      5kW łącznej mocy gwarantuje, że nie zabraknie "decybeli" w
                      przypadku nawet średniej wielkości imprezy plenerowej.
                      Całość oparta została o marki Hand-Box, ADS i Behringer,
                      zapewniające jakość dźwięku na bardzo przyzwoitym
                      poziomie.
                    </div>
                  </div>
                  <div class="col-2">
                    <img
                      style="width: 100%"
                      src="../assets/instruments/036-speaker.svg"
                    />
                  </div>
                </div>
              </q-card>
            </div>
          </div>
        </q-carousel-slide>
        <q-carousel-slide name="lights" class="column no-wrap flex-center">
          <div class="row p-2 pt-0 flex-center-content">
            <div class="text-primary text-h4">
              Oświetlenie
            </div>
          </div>
          <div class="row p-2 flex-center-content">
            <div class="col-8">
              <q-card>
                <div class="row flex-center-content">
                  <img src="../assets/instruments/disco-ball.svg" />
                </div>
                <div class="row">
                  <div
                    class="text-h6 text-primary p-1 flex-center-content text-center"
                  >
                    Imprezowy klimat zapewnimy także dzięki odpowiedniemu
                    oświetleniu sceny i sali (terenu przy scenie), realizowanemu
                    przy pomocy 4 skanerów, 4 lamp typu par, oraz kilku
                    dodatkowych świateł.
                  </div>
                </div>
              </q-card>
            </div>
          </div>
        </q-carousel-slide>
      </q-carousel>
    </div>

    <!-- Terminarz -->
    <div class="full-width pt-2">
      <div class="row p-2 pt-0 pb-0">
        <div class="col-12 p-2">
          <div class="text-primary text-h3 mb-2">
            Terminarz
          </div>
          <q-separator class="separator mb-2" />
        </div>
      </div>
      <div class="row p-2 pt-0 full-width">
        <div class="col-6 p-2 pt-0">
          <q-date class="full-width" v-model="date" dark landscape />
        </div>
        <div class="col-6 p-2 pt-0">
          <div class="text-primary text-body1 text-justify mb-2">
            Obok znajduje się terminarz, dzięki któremu możesz szybko
            zorientować się, czy termin, który Cię interesuje jest wolny, czy
            zajęty. Oczywiście informacje te należy traktować jako orientacyjne,
            a 100% pewność można uzyskać po skontaktowaniu się z nami
            bezpośrednio.
          </div>
        </div>
      </div>
    </div>

    <!-- Kontakt -->
    <div class="full-width">
      <img
        class="relative-position"
        style="transform: translateY(6px)"
        src="../assets/page-decorator-up.svg"
      />
    </div>
    <div class="full-width bg-primary">
      <div class="row p-2 pt-1 flex-center-content">
        <div class="text-secondary text-h3">
          Kontakt
        </div>
      </div>
      <div class="row p-2">
        <div class="col-6">
          <div class="row p-2 pt-0 flex-center-content">
            <div class="text-secondary text-h5">
              Wypełnij i wyślij poniższy formularz...
            </div>
          </div>
          <div class="row p-2 pt-0 flex-center-content">
            <div class="col-12">
              <q-input
                color="secondary"
                filled
                dense
                dark
                label="Imię"
                :rules="[val => !!val || 'Pole jest wymagane']"
              />
              <q-input
                color="secondary"
                filled
                dense
                dark
                label="Nazwisko"
                :rules="[val => !!val || 'Pole jest wymagane']"
              />
              <q-input
                color="secondary"
                filled
                dense
                dark
                label="Miejscowość"
                :rules="[val => !!val || 'Pole jest wymagane']"
              />
              <q-input
                color="secondary"
                type="email"
                filled
                dense
                dark
                label="Adres e-mail"
                :rules="[val => !!val || 'Pole jest wymagane']"
              />
              <q-input
                color="secondary"
                type="tel"
                filled
                dense
                dark
                label="Numer telefonu"
              />
              <br /><br />
              <q-input
                color="secondary"
                autogrow
                filled
                dense
                dark
                label="Treść wiadomości"
                :rules="[val => !!val || 'Pole jest wymagane']"
              />
            </div>
          </div>
        </div>
        <div class="col-6">
          <div class="row p-2 pt-0 flex-center-content">
            <div class="text-secondary text-h5">
              ...lub skontaktuj się z nami bezpośrednio.
            </div>
          </div>
          <div class="row p-2 pt-0 flex-center-content">
            <div class="col-12">
              <q-input
                color="secondary"
                filled
                dense
                dark
                label="Imię"
                :rules="[val => !!val || 'Pole jest wymagane']"
              />
              <q-input
                color="secondary"
                filled
                dense
                dark
                label="Nazwisko"
                :rules="[val => !!val || 'Pole jest wymagane']"
              />
              <q-input
                color="secondary"
                filled
                dense
                dark
                label="Miejscowość"
                :rules="[val => !!val || 'Pole jest wymagane']"
              />
              <q-input
                color="secondary"
                type="email"
                filled
                dense
                dark
                label="Adres e-mail"
                :rules="[val => !!val || 'Pole jest wymagane']"
              />
              <q-input
                color="secondary"
                type="tel"
                filled
                dense
                dark
                label="Numer telefonu"
              />
              <br /><br />
              <q-input
                color="secondary"
                autogrow
                filled
                dense
                dark
                label="Treść wiadomości"
                :rules="[val => !!val || 'Pole jest wymagane']"
              />
            </div>
          </div>
        </div>
      </div>
      <div>
        Icons made by
        <a href="https://www.flaticon.com/authors/bqlqn" title="bqlqn">bqlqn</a>
        from
        <a href="https://www.flaticon.com/" title="Flaticon">www.flaticon.com</a>
        is licensed by
        <a
          href="http://creativecommons.org/licenses/by/3.0/"
          title="Creative Commons BY 3.0"
          target="_blank"
        >CC 3.0 BY</a
        >
      </div>
      <div>
        Icons made by
        <a href="https://www.flaticon.com/authors/freepik" title="Freepik"
        >Freepik</a
        >
        from
        <a href="https://www.flaticon.com/" title="Flaticon">www.flaticon.com</a>
        is licensed by
        <a
          href="http://creativecommons.org/licenses/by/3.0/"
          title="Creative Commons BY 3.0"
          target="_blank"
        >CC 3.0 BY</a
        >
      </div>
    </div>
  </q-page>
</template>

<style lang="stylus" scoped>
.main-carousel
  height: 800px

.carousel-shadow-2 > q-carousel__slides-container
  box-shadow 0 1px 5px rgba(0,0,0,0.2), 0 2px 2px rgba(0,0,0,0.14), 0 3px 1px -2px rgba(0,0,0,0.12)


.custom-caption
  text-align center
  vertical-align center
  padding 10%
  color white
  height inherit

.carousel-text-header
  text-shadow 0px 0px 7px #FFFF77
  font-size 3em

.carousel-text
  text-shadow 0px 0px 7px #000
  font-size 1.5em
  line-height 30px

.separator
  height 2px
  background-color $primary
</style>

<script>
export default {
  name: "PageIndex",
  data() {
    return {
      slideImages: 1,
      slideVideo: "Rihanna",
      slideGallery: 1,
      slideInstruments: "main",
      date: "2019/02/01"
    };
  }
};
</script>
