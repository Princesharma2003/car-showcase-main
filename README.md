 
 
.hero__title {
  @apply 2xl:text-[72px] sm:text-[64px] text-[50px] font-extrabold;
}

.hero__subtitle {
  @apply text-[27px] text-black-100 font-light mt-5;
}

.hero__image-container {
  @apply xl:flex-[1.5] flex justify-end items-end w-full xl:h-screen;
}

.hero__image {
  @apply relative xl:w-full w-[90%] xl:h-full h-[590px] z-0;
}

.hero__image-overlay {
  @apply absolute xl:-top-24 xl:-right-1/2 -right-1/4 bg-hero-bg bg-repeat-round -z-10 w-full xl:h-screen h-[590px] overflow-hidden;
}
/* END: Hero styles */

/* START: Home styles */

.home__text-container {
  @apply flex flex-col items-start justify-start gap-y-2.5 text-black-100;
}

.home__filters {
  @apply mt-12 w-full flex-between items-center flex-wrap gap-5;
}

.home__filter-container {
  @apply flex justify-start flex-wrap items-center gap-2;
}

.home__cars-wrapper {
  @apply grid 2xl:grid-cols-4 xl:grid-cols-3 md:grid-cols-2 grid-cols-1 w-full gap-8 pt-14;
}

.home__error-container {
  @apply mt-16 flex justify-center items-center flex-col gap-2;
}
/* END: Home styles */

/* START: Car Card styles */
.car-card {
  @apply flex flex-col p-6 justify-center items-start text-black-100 bg-primary-blue-100 hover:bg-white hover:shadow-md rounded-3xl;
}

.car-card__content {
  @apply w-full flex justify-between items-start gap-2;
}

.car-card__content-title {
  @apply text-[22px] leading-[26px] font-bold capitalize;
}

.car-card__price {
  @apply flex mt-6 text-[32px] leading-[38px] font-extrabold;
}

.car-card__price-dollar {
  @apply self-start text-[14px] leading-[17px] font-semibold;
 {
 {

