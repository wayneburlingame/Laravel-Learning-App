<template>

    <!-- Dashboard Command Center Menu -->
    <!-- Container -->
    <mdb-container>
    <hr class="mt-4">
    <section class="text-center">

        <!-- Vertical Button Seporater -->
        <mdb-icon icon="grip-lines-vertical" />

        <!-- Dropdown Menus -->
      <mdb-dropdown class="pb-2">
        <mdb-dropdown-toggle slot="toggle" color="light-green" >Dropdown 1</mdb-dropdown-toggle>
        <mdb-dropdown-menu color="light-green">
          <mdb-dropdown-item>Action</mdb-dropdown-item>
          <mdb-dropdown-item>Another action</mdb-dropdown-item>
          <mdb-dropdown-item>Something else here</mdb-dropdown-item>
        </mdb-dropdown-menu>
      </mdb-dropdown>

        <mdb-icon icon="grip-lines-vertical" />
        <mdb-dropdown>
            <mdb-dropdown-toggle slot="toggle" color="primary">Dropdown 2</mdb-dropdown-toggle>
            <mdb-dropdown-menu color="primary">
                <mdb-dropdown-item>Action</mdb-dropdown-item>
                <mdb-dropdown-item>Another action</mdb-dropdown-item>
                <mdb-dropdown-item>Something else here</mdb-dropdown-item>
            </mdb-dropdown-menu>
        </mdb-dropdown>

        <mdb-icon icon="grip-lines-vertical" />
        <mdb-dropdown>
            <mdb-dropdown-toggle slot="toggle" color="purple">Dropdown 2</mdb-dropdown-toggle>
            <mdb-dropdown-menu color="purple">
                <mdb-dropdown-item>Action</mdb-dropdown-item>
                <mdb-dropdown-item>Another action</mdb-dropdown-item>
                <mdb-dropdown-item>Something else here</mdb-dropdown-item>
            </mdb-dropdown-menu>
        </mdb-dropdown>

        <mdb-icon icon="grip-lines-vertical" />
            <mdb-dropdown>
                <mdb-dropdown-toggle slot="toggle" color="indigo">Dropdown 2</mdb-dropdown-toggle>
                <mdb-dropdown-menu color="indigo">
                    <mdb-dropdown-item>Action</mdb-dropdown-item>
                    <mdb-dropdown-item>Another action</mdb-dropdown-item>
                    <mdb-dropdown-item>Something else here</mdb-dropdown-item>
                </mdb-dropdown-menu>
            </mdb-dropdown>

        <mdb-icon icon="grip-lines-vertical" />
            <mdb-dropdown>
                <mdb-dropdown-toggle slot="toggle" color="indigo">Dropdown 2</mdb-dropdown-toggle>
                <mdb-dropdown-menu color="indigo">
                    <mdb-dropdown-item>Action</mdb-dropdown-item>
                    <mdb-dropdown-item>Another action</mdb-dropdown-item>
                    <mdb-dropdown-item>Something else here</mdb-dropdown-item>
                </mdb-dropdown-menu>
            </mdb-dropdown>

        <mdb-icon icon="grip-lines-vertical" />
            <mdb-dropdown>
                <mdb-dropdown-toggle slot="toggle" color="indigo">Dropdown 2</mdb-dropdown-toggle>
                <mdb-dropdown-menu color="indigo">
                    <mdb-dropdown-item>Action</mdb-dropdown-item>
                    <mdb-dropdown-item>Another action</mdb-dropdown-item>
                    <mdb-dropdown-item>Something else here</mdb-dropdown-item>
                </mdb-dropdown-menu>
            </mdb-dropdown>

        <mdb-icon icon="grip-lines-vertical" />
            <mdb-dropdown>
                <mdb-dropdown-toggle slot="toggle" color="indigo">Dropdown 2</mdb-dropdown-toggle>
                <mdb-dropdown-menu color="indigo">
                    <mdb-dropdown-item>Action</mdb-dropdown-item>
                    <mdb-dropdown-item>Another action</mdb-dropdown-item>
                    <mdb-dropdown-item>Something else here</mdb-dropdown-item>
                </mdb-dropdown-menu>
            </mdb-dropdown>

        <mdb-icon icon="grip-lines-vertical" />
      <mdb-dropdown>
        <mdb-dropdown-toggle slot="toggle" color="indigo">Dropdown 2</mdb-dropdown-toggle>
        <mdb-dropdown-menu color="indigo">
          <mdb-dropdown-item>Action</mdb-dropdown-item>
          <mdb-dropdown-item>Another action</mdb-dropdown-item>
          <mdb-dropdown-item>Something else here</mdb-dropdown-item>
        </mdb-dropdown-menu>
      </mdb-dropdown>

        <mdb-icon icon="grip-lines-vertical" />
      <mdb-dropdown>
        <mdb-dropdown-toggle slot="toggle" color="cyan">Reports</mdb-dropdown-toggle>
        <mdb-dropdown-menu color="cyan">
          <mdb-dropdown-item>Action</mdb-dropdown-item>
          <mdb-dropdown-item>Another action</mdb-dropdown-item>
          <mdb-dropdown-item>Something else here</mdb-dropdown-item>
        </mdb-dropdown-menu>
      </mdb-dropdown>

        <mdb-icon icon="grip-lines-vertical" />
        <mdb-dropdown>
            <mdb-dropdown-toggle slot="toggle" color="elegant">API CONFIG</mdb-dropdown-toggle>
            <mdb-dropdown-menu  color="elegant">
                <mdb-dropdown-item>Action</mdb-dropdown-item>
                <mdb-dropdown-item>Another action</mdb-dropdown-item>
                <mdb-dropdown-item>Something else here</mdb-dropdown-item>
            </mdb-dropdown-menu>
        </mdb-dropdown>

        <mdb-icon icon="grip-lines-vertical" />
      <mdb-dropdown class="pb-2">
        <mdb-dropdown-toggle slot="toggle" color="deep-orange">Maintenance</mdb-dropdown-toggle>
        <mdb-dropdown-menu color="deep-orange">
          <mdb-dropdown-item>Action</mdb-dropdown-item>
          <mdb-dropdown-item>Another action</mdb-dropdown-item>
          <mdb-dropdown-item>Something else here</mdb-dropdown-item>
        </mdb-dropdown-menu>
      </mdb-dropdown>

        <mdb-icon icon="grip-lines-vertical" />
      <mdb-dropdown>
        <mdb-dropdown-toggle slot="toggle" color="danger">Admin Only</mdb-dropdown-toggle>
        <mdb-dropdown-menu color="danger">
          <mdb-dropdown-item>Action</mdb-dropdown-item>
          <mdb-dropdown-item>Another action</mdb-dropdown-item>
          <mdb-dropdown-item>Something else here</mdb-dropdown-item>
        </mdb-dropdown-menu>
      </mdb-dropdown>

        <mdb-icon icon="grip-lines-vertical" />
        <mdb-dropdown></mdb-dropdown>
    </section>
  </mdb-container>

</template>

<script>
import { mdbContainer, mdbRow, mdbCol, mdbBadge, mdbBtn, mdbIcon, mdbNavbar, mdbNavItem, mdbNavbarNav, mdbNavbarToggler, mdbInput, mdbTextarea, mdbBreadcrumb, mdbBreadcrumbItem, mdbDropdown, mdbDropdownToggle, mdbDropdownMenu, mdbDropdownItem, mdbCard,  mdbCardImage, mdbCardHeader, mdbCardFooter, mdbCardBody, mdbTbl, mdbTblHead, mdbTblBody, mdbPagination, mdbPageItem,mdbMedia,mdbMediaImage,mdbMediaBody, mdbListGroup, mdbListGroupItem, mdbLineChart, mdbRadarChart, mdbBarChart, mdbPolarChart, mdbPieChart, mdbDoughnutChart, mdbView, mdbMask, mdbEdgeHeader } from 'mdbvue';

export default {
  name: 'DropdownWidgets',
  components: {
    mdbContainer,
    mdbRow,
    mdbCol,
    mdbBtn,
    mdbBadge,
    mdbIcon,
    mdbNavbar,
    mdbNavItem,
    mdbNavbarNav,
    mdbNavbarToggler,
    mdbInput,
    mdbTextarea,
    mdbBreadcrumb,
    mdbBreadcrumbItem,
    mdbDropdown,
    mdbDropdownToggle,
    mdbDropdownMenu,
    mdbDropdownItem,
    mdbCard,
    mdbCardImage,
    mdbCardHeader,
    mdbCardFooter,
    mdbCardBody,
    mdbTbl,
    mdbTblHead,
    mdbTblBody,
    mdbPagination,
    mdbPageItem,
    mdbMedia,
    mdbMediaImage,
    mdbMediaBody,
    mdbListGroup,
    mdbListGroupItem,
    mdbLineChart,
    mdbRadarChart,
    mdbBarChart,
    mdbPolarChart,
    mdbPieChart,
    mdbDoughnutChart,
    mdbView,
    mdbMask,
    mdbEdgeHeader
  },

  methods: {
    toggleDropdown(index) {
      for (let i = 0; i < Object.keys(this.active).length; i++) {
        if (index !== i) {
          this.active[i] = false;
        }
      }
      this.active[index] = !this.active[index];
    },
    allDropdownsClose() {
      for (let i = 0; i < Object.keys(this.active).length; i++) {
        this.active[i] = false;
      }
    },
    onClick(e) {
      let parent = e.target;
      let body = document.getElementsByTagName('body')[0];
      while (parent !== body) {
        if (parent.classList.contains('dropdown') || parent.classList.contains('btn-group')) {
          return;
        }
        parent = parent.parentNode;
      }
      this.allDropdownsClose(e.target);
    }
  },
  mounted() {
    document.addEventListener('click', this.onClick);
  },
  destroyed() {
    document.removeEventListener('click', this.onClick);
  }
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h1 {
  margin: 50px 0;
}
h1, h2, h5 {
  text-align: center;
}
.container > p {
  margin-bottom: 80px;
  text-align: center;
}
section {
  padding-bottom: 40px;
}
section > h2 {
  font-weight: 500;
  margin: 50px 0;
}
section > h5 {
  margin: 30px 0;
}
.media {
  text-align: left;
}
.navbar .dropdown-menu a:hover {
  color: inherit !important;
}
form h5 {
  text-align: left;
}
</style>
