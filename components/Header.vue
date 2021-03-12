<template>
  <div id="header">
    <img class="header-img" src="~@/assets/header.jpg" />
    <div class="header-index">
      <NuxtLink to="/">
        <img
          :show="!onHome"
          :hidden="onHome"
          src="~@/assets/header_home.jpg"
          @mouseover="overHome()"
        />
        <img
          :show="onHome"
          :hidden="!onHome"
          src="~@/assets/header_home_hover.jpg"
          @mouseleave="leaveHome()"
        />
      </NuxtLink>
      <NuxtLink to="/about">
        <img
          :show="!onAbout"
          :hidden="onAbout"
          src="~@/assets/header_about.jpg"
          @mouseover="overAbout()"
        />
        <img
          :show="onAbout"
          :hidden="!onAbout"
          src="~@/assets/header_about_hover.jpg"
          @mouseleave="leaveAbout()"
        />
      </NuxtLink>
      <NuxtLink to="/asobo">
        <img
          :show="!onAsobo"
          :hidden="onAsobo"
          src="~@/assets/header_asobo.jpg"
          @mouseover="overAsobo()"
        />
        <img
          :show="onAsobo"
          :hidden="!onAsobo"
          src="~@/assets/header_asobo_hover.jpg"
          @mouseleave="leaveAsobo()"
        />
      </NuxtLink>
      <NuxtLink to="/camp">
        <img
          :show="!onCamp"
          :hidden="onCamp"
          src="~@/assets/header_camp.jpg"
          @mouseover="overCamp()"
        />
        <img
          :show="onCamp"
          :hidden="!onCamp"
          src="~@/assets/header_camp_hover.jpg"
          @mouseleave="leaveCamp()"
        />
      </NuxtLink>
      <NuxtLink to="/photo">
        <img
          :show="!onPicture"
          :hidden="onPicture"
          src="~@/assets/header_picture.jpg"
          @mouseover="overPicture()"
        />
        <img
          :show="onPicture"
          :hidden="!onPicture"
          src="~@/assets/header_picture_hover.jpg"
          @mouseleave="leavePicture()"
        />
      </NuxtLink>
      <NuxtLink to="/access">
        <img
          :show="!onAccess"
          :hidden="onAccess"
          src="~@/assets/header_access.jpg"
          @mouseover="overAccess()"
        />
        <img
          :show="onAccess"
          :hidden="!onAccess"
          src="~@/assets/header_access_hover.jpg"
          @mouseleave="leaveAccess()"
        />
      </NuxtLink>
      <NuxtLink to="/volunteer">
        <img
          :show="!onVolunteer"
          :hidden="onVolunteer"
          src="~@/assets/header_volunteer.jpg"
          @mouseover="overVolunteer()"
        />
        <img
          :show="onVolunteer"
          :hidden="!onVolunteer"
          src="~@/assets/header_volunteer_hover.jpg"
          @mouseleave="leaveVolunteer()"
        />
      </NuxtLink>
      <NuxtLink to="/records">
        <img
          :show="!onRecord"
          :hidden="onRecord"
          src="~@/assets/header_record.jpg"
          @mouseover="overRecord()"
        />
        <img
          :show="onRecord"
          :hidden="!onRecord"
          src="~@/assets/header_record_hover.jpg"
          @mouseleave="leaveRecord()"
        />
      </NuxtLink>
    </div>
  </div>
</template>

<script>
export default {
  data() {
    return {
      onHome: false,
      onAbout: false,
      onAsobo: false,
      onCamp: false,
      onPicture: false,
      onAccess: false,
      onVolunteer: false,
      onRecord: false,
    }
  },
  methods: {
    overHome() {
      this.onHome = true
    },
    leaveHome() {
      this.onHome = false
    },
    overAbout() {
      this.onAbout = true
    },
    leaveAbout() {
      this.onAbout = false
    },
    overAsobo() {
      this.onAsobo = true
    },
    leaveAsobo() {
      this.onAsobo = false
    },
    overCamp() {
      this.onCamp = true
    },
    leaveCamp() {
      this.onCamp = false
    },
    overPicture() {
      this.onPicture = true
    },
    leavePicture() {
      this.onPicture = false
    },
    overAccess() {
      this.onAccess = true
    },
    leaveAccess() {
      this.onAccess = false
    },
    overVolunteer() {
      this.onVolunteer = true
    },
    leaveVolunteer() {
      this.onVolunteer = false
    },
    overRecord() {
      this.onRecord = true
    },
    leaveRecord() {
      this.onRecord = false
    },
  },
}
</script>

<style scoped>
.header-img {
  width: 100%;
  max-width: 950px;
  text-align: center;
}

.header-index {
  width: 100%;
  max-width: 950px;
  display: flex;
  flex-wrap: nowrap;
}

.header-index img {
  margin: 0px 0px 20px 0px;
  flex: 1.1, 1, auto;
  cursor: pointer;
}

@media screen and (max-width: 480px) {
  .header-index {
    overflow-x: auto;
  }

  .header-index img {
    height: 35px;
  }
}
</style>
