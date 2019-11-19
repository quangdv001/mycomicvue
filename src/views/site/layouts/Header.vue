<template>
    <b-container fluid class="header bg-dark">
        <b-navbar toggleable="lg" type="dark" variant="dark">
            <b-navbar-brand href="#">NavBar</b-navbar-brand>

            <b-navbar-toggle target="nav-collapse"></b-navbar-toggle>

            <b-collapse id="nav-collapse" is-nav>
                <b-navbar-nav>
                    <router-link to="/"><b-nav-item active href="javascript:void(0);" class="text-left">Trang chủ</b-nav-item></router-link>
                    <router-link to="/detail"><b-nav-item href="javascript:void(0);" class="text-left">Chi tiết</b-nav-item></router-link>
                    <router-link to="/chapter"><b-nav-item href="javascript:void(0);" class="text-left">Nội dung</b-nav-item></router-link>
                    <b-nav-item-dropdown text="Thể loại" class="text-left">
                        <b-row class="dropdown-multicol2">
                            <b-col col="12" lg="3">
                                <router-link to="/chapter"><b-dropdown-item href="#">EN</b-dropdown-item></router-link>
                            </b-col>
                            <b-col col="12" lg="3">
                                <router-link to="/chapter"><b-dropdown-item href="#">EN</b-dropdown-item></router-link>
                            </b-col>
                            <b-col col="12" lg="3">
                                <router-link to="/chapter"><b-dropdown-item href="#">EN</b-dropdown-item></router-link>
                            </b-col>
                            <b-col col="12" lg="3">
                                <router-link to="/chapter"><b-dropdown-item href="#">EN</b-dropdown-item></router-link>
                            </b-col>
                            <b-col col="12" lg="3">
                                <router-link to="/chapter"><b-dropdown-item href="#">EN</b-dropdown-item></router-link>
                            </b-col>
                            <b-col col="12" lg="3">
                                <router-link to="/chapter"><b-dropdown-item href="#">EN</b-dropdown-item></router-link>
                            </b-col>
                            <b-col col="12" lg="3">
                                <router-link to="/chapter"><b-dropdown-item href="#">EN</b-dropdown-item></router-link>
                            </b-col>
                            <b-col col="12" lg="3">
                                <router-link to="/chapter"><b-dropdown-item href="#">EN</b-dropdown-item></router-link>
                            </b-col>
                            <b-col col="12" lg="3">
                                <router-link to="/chapter"><b-dropdown-item href="#">EN</b-dropdown-item></router-link>
                            </b-col>
                            <b-col col="12" lg="3">
                                <router-link to="/chapter"><b-dropdown-item href="#">EN</b-dropdown-item></router-link>
                            </b-col>
                            <b-col col="12" lg="3">
                                <router-link to="/chapter"><b-dropdown-item href="#">EN</b-dropdown-item></router-link>
                            </b-col>
                            <b-col col="12" lg="3">
                                <router-link to="/chapter"><b-dropdown-item href="#">EN</b-dropdown-item></router-link>
                            </b-col>
                            <b-col col="12" lg="3">
                                <router-link to="/chapter"><b-dropdown-item href="#">EN</b-dropdown-item></router-link>
                            </b-col>
                            <b-col col="12" lg="3">
                                <router-link to="/chapter"><b-dropdown-item href="#">EN</b-dropdown-item></router-link>
                            </b-col>
                            <b-col col="12" lg="3">
                                <router-link to="/chapter"><b-dropdown-item href="#">EN</b-dropdown-item></router-link>
                            </b-col>
                        </b-row>
                    </b-nav-item-dropdown>
                </b-navbar-nav>

                <!-- Right aligned nav items -->
                <b-navbar-nav class="ml-auto">
                    

                    <b-nav-item-dropdown class="mr-2 text-left">
                        <!-- Using 'button-content' slot -->
                        <template v-slot:button-content>
                            <em>Tài khoản</em>
                        </template>
                        <b-dropdown-item href="#">Profile</b-dropdown-item>
                        <b-dropdown-item href="#">Sign Out</b-dropdown-item>
                    </b-nav-item-dropdown>
                    <b-nav-form>
                        <b-form-input size="sm" class="mr-sm-2" placeholder="Search"></b-form-input>
                        <b-button size="sm" class="my-2 my-sm-0" type="submit">Search</b-button>
                    </b-nav-form>
                </b-navbar-nav>
            </b-collapse>
        </b-navbar>
    </b-container>
</template>

<script>
    export default {

    }
</script>