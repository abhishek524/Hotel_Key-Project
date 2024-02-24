<template>
  <div
    class="w-full relative bg-white overflow-hidden flex flex-col items-center justify-start pt-[1.875rem] px-[0rem] pb-[0rem] box-border gap-[5.625rem_0rem] tracking-[normal] mq750:gap-[5.625rem_0rem] mq450:gap-[5.625rem_0rem]"
  >
    <header
      class="w-[77.188rem] flex flex-row items-center justify-between pt-[0rem] px-[1.25rem] pb-[1.313rem] box-border gap-[1.25rem] max-w-full text-left text-[1rem] text-black font-nunito-sans"
    >
      <img
        class="h-[2rem] w-[8.625rem] relative overflow-hidden shrink-0"
        loading="eager"
        alt=""
        src="/hotelkey-logo11.svg"
      />
      <div
        class="w-[25.688rem] flex flex-row items-center justify-start gap-[0rem_1.438rem] max-w-full"
      >
        <div class="relative font-semibold whitespace-nowrap">About Us</div>
        <div
          class="flex-[0.8922] flex flex-row items-center justify-start p-[0.625rem] gap-[0rem_0.625rem] cursor-pointer"
          :onClick="openProductMenu"
        >
          <div class="relative font-semibold">Products</div>
          <img
            class="h-[1rem] w-[1rem] relative overflow-hidden shrink-0 object-contain"
            alt=""
            src="/eparrowupbold.svg"
          />
        </div>
        <div
          class="flex-1 flex flex-row items-center justify-start py-[0rem] pr-[0.563rem] pl-[0rem] gap-[0rem_0.594rem]"
        >
          <div
            class="h-[0.813rem] flex flex-col items-start justify-start pt-[0rem] px-[0rem] pb-[0.125rem] box-border"
          >
            <img
              class="w-[1rem] h-[0.669rem] relative overflow-hidden shrink-0"
              alt=""
              src="/usa-flag-1.svg"
            />
          </div>
          <div class="relative font-semibold">English</div>
          <img
            class="h-[1rem] w-[1rem] relative overflow-hidden shrink-0 object-contain"
            alt=""
            src="/eparrowupbold.svg"
          />
        </div>
        <Component
          component1Width="3rem"
          component1Height="2.938rem"
          component1Position="relative"
          component1Top="unset"
          component1Left="unset"
          lineDivHeight="6.38%"
          lineDivWidth="56.25%"
          lineDivTop="36.17%"
          lineDivRight="18.75%"
          lineDivBottom="57.45%"
          lineDivLeft="25%"
          lineDivHeight1="6.38%"
          lineDivWidth1="31.25%"
          lineDivTop1="57.45%"
          lineDivRight1="43.75%"
          lineDivBottom1="36.17%"
          lineDivLeft1="25%"
        />
      </div>
    </header>
    <main
      class="w-[75.063rem] flex flex-row items-start justify-start py-[0rem] pr-[0.125rem] pl-[0rem] box-border max-w-full"
    >
      <section
        class="flex-1 flex flex-col items-center justify-start gap-[2.688rem_0rem] max-w-full text-left text-[3rem] text-black font-nunito-sans mq750:gap-[2.688rem_0rem]"
      >
        <div
          class="self-stretch flex flex-col items-start justify-start pt-[6.813rem] px-[5rem] pb-[6.875rem] box-border relative gap-[0.813rem_0rem] max-w-full mq1050:pl-[2.5rem] mq1050:pr-[2.5rem] mq1050:box-border mq450:pt-[4.438rem] mq450:pb-[4.438rem] mq450:box-border"
        >
          <img
            class="w-full h-full absolute !m-[0] top-[0rem] right-[-0.031rem] bottom-[0rem] left-[0.038rem] max-w-full overflow-hidden max-h-full"
            alt=""
            src="/background-img.svg"
          />
          <img
            class="w-[24.375rem] h-[29.938rem] absolute !m-[0] top-[-6.375rem] right-[0.031rem] object-contain z-[1]"
            loading="eager"
            alt=""
            src="/image@2x.png"
          />
          <h1
            class="m-0 h-[7rem] relative text-inherit tracking-[-0.01em] leading-[3.5rem] font-extrabold font-inherit inline-block max-w-full z-[1] mq1050:text-[2.375rem] mq1050:leading-[2.813rem] mq450:text-[1.813rem] mq450:leading-[2.125rem]"
          >
            <p class="m-0">New to HotelKey?</p>
            <p class="m-0">Connect with our sales team.</p>
          </h1>
          <h3
            class="m-0 h-[2.063rem] relative text-[1.5rem] font-semibold font-inherit text-darkslategray-300 inline-block max-w-full z-[1] mq450:text-[1.188rem]"
          >
            Reach out and we’ll get in touch within 24 hours
          </h3>
        </div>
        <div
          class="w-[64rem] flex flex-row items-start justify-start pt-[0rem] pb-[1.313rem] pr-[0rem] pl-[0.125rem] box-border max-w-full mq1050:max-w-[calc(100%_-_2px)]"
        >
          <form
            class="m-0 flex-1 flex flex-col items-start justify-start gap-[2.125rem_0rem] max-w-full mq750:gap-[2.125rem_0rem]"
          >
            <div
              class="self-stretch flex flex-col items-start justify-start gap-[0.75rem_0rem] max-w-full"
            >
              <div
                class="self-stretch flex flex-row items-center justify-start py-[0.875rem] px-[0.25rem] gap-[0rem_0.625rem] border-b-[1px] border-solid border-lightgray"
              >
                <img
                  class="h-[1rem] w-[1rem] relative"
                  alt=""
                  src="/group.svg"
                />
                <input
                  class="w-[9.313rem] [border:none] [outline:none] font-extrabold font-nunito-sans text-[1.5rem] bg-[transparent] h-[2.063rem] relative text-black text-left inline-block mq450:text-[1.188rem]"
                  placeholder="Personal Info"
                  type="text"
                />
              </div>
              <div
                class="self-stretch h-[11.938rem] flex flex-row flex-wrap items-start justify-start relative gap-[1.5rem_1.125rem] max-w-full"
              >
                <div
                  class="w-[31.188rem] !m-[0] absolute top-[0rem] left-[0.031rem] flex flex-col items-start justify-start gap-[0.25rem_0rem] max-w-full"
                >
                  <b
                    class="w-[6.313rem] relative text-[1rem] inline-block font-nunito-sans text-darkslategray-700 text-left box-border pr-[1.25rem]"
                    >First Name</b
                  >
                  <div
                    class="self-stretch h-[3.688rem] rounded-md bg-gray-100 box-border flex flex-row items-center justify-center py-[1.063rem] pr-[20.938rem] pl-[0.625rem] relative gap-[0rem_0.063rem] border-[2px] border-solid border-steelblue"
                  >
                    <div
                      class="h-[1.563rem] w-[0.063rem] absolute !m-[0] top-[1.063rem] left-[0.625rem] box-border border-r-[1px] border-solid border-steelblue"
                    />
                    <input
                      class="w-[9.563rem] [border:none] [outline:none] inline-block font-nunito-sans text-[1rem] bg-[transparent] h-[1.375rem] absolute !m-[0] top-[1.156rem] left-[0.688rem] font-bold text-darkgray-200 text-left"
                      placeholder="Type your first name"
                      type="text"
                    />
                  </div>
                </div>
                <div
                  class="w-[31.188rem] !m-[0] absolute top-[0rem] left-[32.719rem] flex flex-col items-start justify-start gap-[0.25rem_0rem] max-w-full"
                >
                  <b
                    class="w-[6.25rem] relative text-[1rem] inline-block font-nunito-sans text-black text-left box-border pr-[1.25rem]"
                    >Last Name</b
                  >
                  <div
                    class="self-stretch rounded-md bg-gray-100 flex flex-row items-center justify-start py-[1.063rem] px-[0.625rem] border-[1px] border-solid border-gainsboro-200"
                  >
                    <input
                      class="w-[10.813rem] [border:none] [outline:none] inline-block font-nunito-sans text-[1rem] bg-[transparent] h-[1.375rem] relative font-bold text-darkgray-200 text-left"
                      placeholder="Type your first name"
                      type="text"
                    />
                  </div>
                </div>
                <div
                  class="w-[31.188rem] !m-[0] absolute top-[6.813rem] left-[0.031rem] flex flex-col items-start justify-start gap-[0.25rem_0rem] max-w-full"
                >
                  <b
                    class="w-[8.25rem] h-[1.375rem] relative text-[1rem] inline-block font-nunito-sans text-black text-left box-border pr-[1.25rem]"
                    >Phone Number</b
                  >
                  <div
                    class="self-stretch rounded-md bg-gray-100 flex flex-row items-center justify-start py-[1.063rem] px-[0.625rem] border-[1px] border-solid border-gainsboro-200"
                  >
                    <input
                      class="w-[10.813rem] [border:none] [outline:none] inline-block font-nunito-sans text-[1rem] bg-[transparent] h-[1.375rem] relative font-bold text-black text-left whitespace-nowrap"
                      placeholder="+91 771-1233-8178"
                      type="text"
                    />
                  </div>
                </div>
                <div
                  class="w-[31.188rem] !m-[0] absolute top-[6.813rem] left-[32.719rem] flex flex-col items-start justify-start gap-[0.25rem_0rem] max-w-full"
                >
                  <b
                    class="w-[8rem] relative text-[1rem] inline-block font-nunito-sans text-darkslategray-700 text-left box-border pr-[1.25rem]"
                    >Email Address</b
                  >
                  <div
                    class="self-stretch rounded-md bg-gray-100 flex flex-row items-center justify-start py-[1.063rem] px-[0.625rem] border-[1px] border-solid border-gainsboro-200"
                  >
                    <input
                      class="w-[10.938rem] [border:none] [outline:none] inline-block font-nunito-sans text-[1rem] bg-[transparent] h-[1.375rem] relative font-bold text-darkgray-200 text-left whitespace-nowrap"
                      placeholder="example@gmail.com"
                      type="text"
                    />
                  </div>
                </div>
              </div>
            </div>
            <div
              class="self-stretch flex flex-col items-start justify-start gap-[0.75rem_0rem] max-w-full"
            >
              <div
                class="self-stretch flex flex-col items-start justify-start py-[0.875rem] pr-[31.688rem] pl-[0rem] border-b-[1px] border-solid border-lightgray mq750:pr-[15.813rem] mq750:box-border mq450:pr-[1.25rem] mq450:box-border"
              >
                <div
                  class="w-[13.438rem] flex flex-row items-center justify-start gap-[0rem_0.375rem]"
                >
                  <img
                    class="h-[1.5rem] w-[1.5rem] relative overflow-hidden shrink-0"
                    alt=""
                    src="/property-icon.svg"
                  />
                  <input
                    class="w-[calc(100%_-_24px)] [border:none] [outline:none] font-extrabold font-nunito-sans text-[1.5rem] bg-[transparent] h-[2.063rem] flex-1 relative text-black text-left inline-block min-w-[6.938rem] mq450:text-[1.188rem]"
                    placeholder="Property Details"
                    type="text"
                  />
                </div>
              </div>
              <div
                class="self-stretch flex flex-row flex-wrap items-start justify-start gap-[0rem_1.5rem] max-w-full"
              >
                <div
                  class="flex-1 flex flex-col items-start justify-start gap-[0.25rem_0rem] min-w-[15.25rem] max-w-full"
                >
                  <b
                    class="w-[8.375rem] relative text-[1rem] inline-block font-nunito-sans text-black text-left box-border pr-[1.25rem]"
                    >Property Name</b
                  >
                  <div
                    class="self-stretch rounded-md bg-gray-100 flex flex-row items-center justify-center py-[1.063rem] px-[0.625rem] border-[1px] border-solid border-gainsboro-200"
                  >
                    <input
                      class="w-[14.438rem] [border:none] [outline:none] inline-block font-nunito-sans text-[1rem] bg-[transparent] h-[1.375rem] relative font-bold text-darkgray-200 text-left"
                      placeholder="Type your Property Name"
                      type="text"
                    />
                  </div>
                </div>
                <div
                  class="flex-1 flex flex-col items-start justify-start gap-[0.25rem_0rem] min-w-[15.25rem] max-w-full"
                >
                  <b
                    class="w-[7.875rem] relative text-[1rem] inline-block font-nunito-sans text-black text-left box-border pr-[1.25rem]"
                    >Property Type</b
                  >
                  <v-autocomplete
                    class="self-stretch h-[3.5rem]"
                    color="#020202"
                    variant="outlined"
                    :items="['Independent','Dependent']"
                    model-value="Independent"
                  />
                </div>
                <div
                  class="flex-1 flex flex-col items-start justify-start gap-[0.25rem_0rem] min-w-[15.25rem] max-w-full"
                >
                  <b
                    class="w-[5rem] relative text-[1rem] inline-block font-nunito-sans text-black text-left box-border pr-[1.25rem]"
                    >Country</b
                  >
                  <v-autocomplete
                    class="self-stretch h-[3.5rem]"
                    color="#020202"
                    variant="outlined"
                    :items="['India','Pakistan','United States','Australia','Macedonia']"
                    model-value="United States"
                  />
                </div>
              </div>
            </div>
            <div
              class="self-stretch flex flex-col items-start justify-start gap-[0.25rem_0rem]"
            >
              <b
                class="w-[7.688rem] relative text-[1rem] inline-block font-nunito-sans text-darkslategray-700 text-left box-border pr-[1.25rem]"
                >Your Message</b
              >
              <div
                class="self-stretch rounded-md bg-gray-100 flex flex-row items-start justify-start pt-[0.875rem] px-[0.875rem] pb-[5rem] border-[1px] border-solid border-gainsboro-200"
              >
                <input
                  class="w-[12.938rem] [border:none] [outline:none] inline-block font-nunito-sans text-[1rem] bg-[transparent] h-[1.375rem] relative font-bold text-darkgray-200 text-left"
                  placeholder="Write your message here"
                  type="text"
                />
              </div>
            </div>
            <button
              class="cursor-pointer [border:none] p-[0.75rem] bg-steelblue w-[8.438rem] rounded-md flex flex-row items-center justify-center box-border hover:bg-deepskyblue"
            >
              <div
                class="w-[5.938rem] relative text-[1rem] font-extrabold font-nunito-sans text-white text-left inline-block box-border pl-[1.25rem] pr-[1.25rem]"
              >
                Submit
              </div>
            </button>
          </form>
        </div>
        <div
          class="self-stretch flex flex-row items-start justify-start pt-[0rem] pb-[2.375rem] pr-[0.063rem] pl-[0.125rem] box-border max-w-full text-[1rem] text-darkslategray-700"
        >
          <div
            class="flex-1 flex flex-col items-start justify-start gap-[4.938rem_0rem] max-w-full lg:gap-[4.938rem_0rem] mq750:gap-[4.938rem_0rem]"
          >
            <div
              class="self-stretch flex flex-row flex-wrap items-start justify-start gap-[0rem_1.875rem] max-w-full"
            >
              <EmailUs
                contactInfoText="/materialsymbolsalternateemail.svg"
                contactInfoLabel="Email us:"
                contactMethod="sales@hotelkeyapp.com"
              />
              <div
                class="flex-1 [background:linear-gradient(180deg,_#f3f3f3,_rgba(250,_250,_250,_0))] flex flex-col items-start justify-start py-[2.375rem] px-[4.688rem] box-border gap-[0.125rem_0rem] min-w-[19.313rem] max-w-full mq750:pl-[2.313rem] mq750:pr-[2.313rem] mq750:box-border"
              >
                <div
                  class="flex flex-row items-start justify-start gap-[0rem_0.438rem]"
                >
                  <img
                    class="h-[1.5rem] w-[1.5rem] relative overflow-hidden shrink-0 min-h-[1.5rem]"
                    loading="eager"
                    alt=""
                    src="/biwhatsapp.svg"
                  />
                  <div
                    class="h-[1.375rem] relative font-extrabold inline-block"
                  >
                    Contact Sales:
                  </div>
                </div>
                <div
                  class="self-stretch flex flex-row items-start justify-start py-[0rem] pr-[0rem] pl-[2rem]"
                >
                  <div
                    class="h-[1.375rem] flex-1 flex flex-row items-start justify-start gap-[0rem_0.813rem]"
                  >
                    <div
                      class="flex-1 relative font-semibold whitespace-nowrap"
                    >
                      +1 972-972-9110
                    </div>
                    <div
                      class="h-[1.375rem] w-[0.063rem] relative box-border border-r-[1px] border-solid border-black"
                    />
                    <div
                      class="flex-1 relative font-semibold whitespace-nowrap"
                    >
                      +1 840-177-5500
                    </div>
                  </div>
                </div>
              </div>
              <EmailUs
                contactInfoText="/micall.svg"
                contactInfoLabel="Contact us on"
                propPadding="2.375rem"
              />
            </div>
            <div
              class="self-stretch flex flex-row flex-wrap items-start justify-start gap-[0rem_1.875rem] max-w-full text-[1.5rem] text-white"
            >
              <div
                class="flex-1 rounded-3xs overflow-hidden flex flex-row items-center justify-center min-w-[23.688rem] max-w-full mq450:min-w-full"
              >
                <div
                  class="flex-1 flex flex-row items-center justify-start max-w-full"
                >
                  <div class="h-[18.313rem] w-[36.438rem] relative max-w-full">
                    <img
                      class="absolute top-[0rem] left-[0rem] w-full h-full object-contain"
                      loading="eager"
                      alt=""
                      src="/support-img@2x.png"
                    />
                    <div
                      class="absolute top-[18.313rem] left-[36.438rem] [background:linear-gradient(90.11deg,_rgba(1,_1,_1,_0.65),_rgba(0,_0,_0,_0))] w-full h-full [transform:_rotate(180deg)] [transform-origin:0_0] z-[1]"
                    />
                  </div>
                  <div
                    class="w-[13.875rem] flex flex-col items-start justify-start py-[1.25rem] px-[0rem] box-border gap-[1rem_0rem] z-[2] ml-[-16.562rem]"
                  >
                    <h3
                      class="m-0 self-stretch relative text-inherit font-bold font-inherit mq450:text-[1.188rem]"
                    >
                      Are you Looking for Support
                    </h3>
                    <button
                      class="cursor-pointer p-[0.563rem] bg-[transparent] w-[6.25rem] rounded-md box-border flex flex-row items-center justify-center border-[1px] border-solid border-white hover:bg-gainsboro-600 hover:box-border hover:border-[1px] hover:border-solid hover:border-gainsboro-100"
                    >
                      <div
                        class="relative text-[1rem] font-nunito-sans text-white text-left"
                      >
                        Connect
                      </div>
                    </button>
                  </div>
                </div>
              </div>
              <div
                class="flex-1 rounded-3xs overflow-hidden flex flex-row items-center justify-center min-w-[23.688rem] max-w-full mq450:min-w-full"
              >
                <div
                  class="flex-1 flex flex-row items-center justify-start py-[0rem] pr-[2.25rem] pl-[0rem] box-border max-w-full"
                >
                  <div
                    class="h-[18.313rem] flex-1 relative shrink-0 max-w-[107%]"
                  >
                    <img
                      class="absolute top-[0rem] left-[0rem] w-full h-full object-cover"
                      loading="eager"
                      alt=""
                      src="/rectangle-12@2x.png"
                    />
                    <div
                      class="absolute top-[18.313rem] left-[36.438rem] rounded-3xs [background:linear-gradient(90.12deg,_rgba(1,_1,_1,_0.88),_rgba(0,_0,_0,_0))] w-full h-full [transform:_rotate(180deg)] [transform-origin:0_0] z-[1]"
                    />
                  </div>
                  <div
                    class="w-[13.813rem] flex flex-col items-start justify-start py-[1.25rem] px-[0rem] box-border gap-[1rem_0rem] z-[2] ml-[-16.062rem]"
                  >
                    <h3
                      class="m-0 self-stretch relative text-inherit font-bold font-inherit mq450:text-[1.188rem]"
                    >
                      Looking to join our team?
                    </h3>
                    <div
                      class="w-[6.438rem] rounded-md box-border flex flex-row items-center justify-center py-[0.563rem] pr-[0.938rem] pl-[1.188rem] whitespace-nowrap text-[1rem] border-[1px] border-solid border-white"
                    >
                      <div class="relative">Yes, I am</div>
                    </div>
                  </div>
                </div>
              </div>
            </div>
          </div>
        </div>
        <frame />
      </section>
    </main>
    <FooterBg />
  </div>
  <div v-if="isProductMenuOpen">
    <PortalPopup
      overlayColor="rgba(113, 113, 113, 0.3)"
      placement="Centered"
      :relativeLayerRef="$refs[productButtonContainerRef]"
      :onOutsideClick="closeProductMenu"
    >
      <ProductMenu :onClose="closeProductMenu" />
    </PortalPopup>
  </div>
</template>
<script>
  import { defineComponent } from "vue";
  import ProductMenu from "../components/product-menu.vue";
  import PortalPopup from "../components/portal-popup.vue";
  import Component from "../components/component.vue";
  import EmailUs from "../components/email-us.vue";
  import Frame from "../components/frame.vue";
  import FooterBg from "../components/footer-bg.vue";

  export default defineComponent({
    name: "ContactPage",
    data() {
      return { isProductMenuOpen: false };
    },
    components: {
      ProductMenu,
      PortalPopup,
      Component,
      EmailUs,
      Frame,
      FooterBg,
    },
    methods: {
      openProductMenu() {
        this.isProductMenuOpen = true;
      },
      closeProductMenu() {
        this.isProductMenuOpen = false;
      },
    },
  });
</script>
