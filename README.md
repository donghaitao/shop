# shop
商城
//## Dark blue theme color file
@import "compass";
@import 'variables';
@import "mixins";
// global metronic framework variables

// Theme Colors Settigns

// Main settings
$theme-name: "darkblue";
$brand-main-color: #1caf9a !default;
$brand-main-font-color: #ffffff !default;

// Body and header
$bg-color: #364150 !default;
$header-bg-color: #2b3643 !default;

// Mega Menu 
$header-hor-menu-bg-color: $header-bg-color;
$header-hor-menu-fixed-border-box: 0px 1px 10px 0px rgba($header-hor-menu-bg-color, 0.2);

//** Default Mega Menu
$header-hor-menu-mega-menu-header-font-color: lighten($header-hor-menu-bg-color, 60%);

$header-hor-menu-default-link-font-color: lighten($header-hor-menu-bg-color, 60%);
$header-hor-menu-default-link-font-color-on-hover: lighten($header-hor-menu-default-link-font-color, 5%);
$header-hor-menu-default-link-font-color-on-active: lighten($header-hor-menu-default-link-font-color, 30%);

$header-hor-menu-default-link-icon-color: lighten($header-hor-menu-bg-color, 35%);
$header-hor-menu-default-link-icon-color-on-hover: lighten($header-hor-menu-default-link-icon-color, 5%);
$header-hor-menu-default-link-icon-color-on-active: lighten($header-hor-menu-default-link-icon-color, 30%);

$header-hor-menu-default-link-bg-color-on-hover: lighten($header-bg-color, 10%);
$header-hor-menu-default-link-bg-color-on-active: $brand-main-color;

// Default Mega Menu Sub Menu 
$header-hor-menu-dropdown-menu-bg-color: $header-hor-menu-default-link-bg-color-on-hover;
$header-hor-menu-box-shadow: 5px 5px rgba($header-hor-menu-dropdown-menu-bg-color, 0.2);

$header-hor-menu-dropdown-menu-link-bg-color-on-active: lighten($header-hor-menu-default-link-bg-color-on-hover, 4%);
$header-hor-menu-dropdown-menu-link-bg-color-on-hover: lighten($header-hor-menu-default-link-bg-color-on-hover, 4%);

$header-hor-menu-dropdown-menu-link-font-color: lighten($header-hor-menu-bg-color, 60%);
$header-hor-menu-dropdown-menu-link-font-color-on-hover: lighten($header-hor-menu-dropdown-menu-link-font-color, 14%);
$header-hor-menu-dropdown-menu-link-font-color-on-active: lighten($header-hor-menu-dropdown-menu-link-font-color, 14%);

$header-hor-menu-dropdown-menu-link-icon-color: lighten($header-hor-menu-dropdown-menu-link-font-color, 0%);
$header-hor-menu-dropdown-menu-link-icon-color-on-hover: lighten($header-hor-menu-dropdown-menu-link-icon-color, 14%);
$header-hor-menu-dropdown-menu-link-icon-color-on-active: lighten($header-hor-menu-dropdown-menu-link-icon-color, 14%);

//** Light Mega Menu
$header-light-hor-menu-mega-menu-header-font-color: #666;

$header-light-hor-menu-default-link-font-color: $header-hor-menu-default-link-font-color;
$header-light-hor-menu-default-link-font-color-on-hover: $header-hor-menu-default-link-font-color-on-hover;
$header-light-hor-menu-default-link-font-color-on-active: $header-hor-menu-default-link-font-color-on-active;

$header-light-hor-menu-default-link-icon-color: $header-hor-menu-default-link-icon-color;
$header-light-hor-menu-default-link-icon-color-on-hover: $header-hor-menu-default-link-icon-color-on-hover;
$header-light-hor-menu-default-link-icon-color-on-active: $header-hor-menu-default-link-icon-color-on-active;

$header-light-hor-menu-default-link-bg-color-on-hover: $header-hor-menu-default-link-bg-color-on-hover;
$header-light-hor-menu-default-link-bg-color-on-active: $header-hor-menu-default-link-bg-color-on-active;

$header-light-hor-menu-default-link-bg-color-on-onen: lighten(#FAFAFC, 2%);
$header-light-hor-menu-default-link-font-color-on-onen: #333;
$header-light-hor-menu-default-link-icon-color-on-onen: #333;

// Light Mega Menu Sub Menu 
$header-light-hor-menu-dropdown-menu-bg-color: $header-light-hor-menu-default-link-bg-color-on-onen;
$header-light-hor-menu-box-shadow: 5px 5px rgba(#666, 0.1);

$header-light-hor-menu-dropdown-menu-link-bg-color-on-active: darken($header-light-hor-menu-dropdown-menu-bg-color, 4%);
$header-light-hor-menu-dropdown-menu-link-bg-color-on-hover: darken($header-light-hor-menu-dropdown-menu-bg-color, 4%);

$header-light-hor-menu-dropdown-menu-link-font-color: #000;
$header-light-hor-menu-dropdown-menu-link-font-color-on-hover: #000;
$header-light-hor-menu-dropdown-menu-link-font-color-on-active: #000;

$header-light-hor-menu-dropdown-menu-link-icon-color: #888;
$header-light-hor-menu-dropdown-menu-link-icon-color-on-hover: #666;
$header-light-hor-menu-dropdown-menu-link-icon-color-on-active: #666;

// Header search
$header-search-bg-color: darken($header-bg-color, 4%) !default;
$header-search-bg-hover-color: $header-hor-menu-default-link-bg-color-on-hover !default;
$header-search-bg-color-on-open: $header-search-bg-hover-color !default;
$header-search-font-color: #959fad !default;
$header-search-placeholder-font-color: darken($header-search-font-color, 1%) !default;

// Top menu
$header-top-menu-bg-hover-color: $header-hor-menu-default-link-bg-color-on-hover !default;
$header-top-menu-bg-hover-color-on-dropdown-open: $header-hor-menu-default-link-bg-color-on-hover !default;
$header-top-menu-badge-bg-color: $brand-main-color;
$header-top-menu-badge-font-color: #ffffff;
$header-top-menu-icon-font-color: lighten(#606d80, 10%) !default;

// Top menu user bar
$header-top-menu-user-font-color: $header-hor-menu-default-link-font-color !default;
$header-top-menu-user-bg-color: $header-search-bg-color !default;

//begin: Top Menu Extended Dropdowns
$header-top-menu-extended-dropdown-item-bg-color-on-hover: #f8f9fa;
$header-top-menu-extended-dropdown-item-border-color: #EFF2F6;
$header-top-menu-extended-dropdown-item-font-color: #888888;

$header-top-menu-extended-dropdown-header-bg-color: darken(#f7f8fa, 4%);
$header-top-menu-extended-dropdown-border-color: darken($header-top-menu-extended-dropdown-header-bg-color, 1%);
$header-top-menu-extended-dropdown-header-font-color: darken(#6f949c, 5%);

$header-top-menu-inbox-dropdown-from-font-color: #5b9bd1;

$header-top-menu-task-dropdown-progress-bg-color: #dfe2e9;

$header-top-menu-notification-time-bg-color: lighten(#eee, 1%);

// Top Menu Notifications
$header-top-menu-dropdown-dark-bg-color: lighten($header-hor-menu-bg-color, 10%);
$header-top-menu-dropdown-dark-header-bg-color: lighten($header-hor-menu-bg-color, 2%);
$header-top-menu-dropdown-dark-header-font-color: lighten($header-top-menu-dropdown-dark-header-bg-color, 50%);

$header-top-menu-dropdown-dark-item-font-color: lighten($header-top-menu-dropdown-dark-header-bg-color, 55%);
$header-top-menu-dropdown-dark-item-border-color: lighten($header-top-menu-dropdown-dark-bg-color, 6%);
$header-top-menu-dropdown-dark-item-icon-color: lighten($header-top-menu-dropdown-dark-header-bg-color, 45%);
$header-top-menu-dropdown-dark-item-bg-color-on-hover: lighten($header-top-menu-dropdown-dark-bg-color, 4%);

$header-top-menu-dropdown-dark-default-menu-divider: $header-top-menu-dropdown-dark-item-border-color;
$header-top-menu-dropdown-dark-notification-time-bg-color: darken($header-top-menu-dropdown-dark-bg-color, 5%);
//end: Top Menu Extended Dropdowns

// Sidebar menu
$sidebar-menu-devider-border-color: darken(#3f4b5a, 1%) !default;

$sidebar-menu-link-font-color: #b4bcc8 !default;
$sidebar-menu-link-font-color-on-hover: $sidebar-menu-link-font-color !default;
$sidebar-menu-link-font-color-on-active: #ffffff !default;

$sidebar-menu-link-icon-font-color: #606C7D !default;
$sidebar-menu-link-icon-font-color-on-active: $sidebar-menu-link-font-color-on-active !default;
$sidebar-menu-link-icon-font-color-on-hover: $sidebar-menu-link-icon-font-color !default;

$sidebar-menu-link-bg-color-on-hover: #2C3542 !default;
$sidebar-menu-link-bg-color-on-active: $brand-main-color;

$sidebar-menu-arrow-color: $sidebar-menu-link-icon-font-color !default;
$sidebar-menu-arrow-color-on-active: $sidebar-menu-link-font-color-on-active !default;
$sidebar-menu-arrow-color-on-hover: $sidebar-menu-link-icon-font-color-on-hover !default;

$sidebar-menu-sub-menu-box-shadow-color: $sidebar-menu-link-bg-color-on-hover !default;
$sidebar-menu-sub-menu-link-font-color: #b4bcc8 !default;
$sidebar-menu-sub-menu-link-icon-font-color: $sidebar-menu-arrow-color !default;
$sidebar-menu-sub-menu-link-bg-color-on-hover: lighten($bg-color, 4%) !default;
$sidebar-menu-sub-menu-link-icon-font-color-on-hover: $sidebar-menu-link-icon-font-color-on-hover !default;

$sidebar-menu-hover-sub-menu-bg-color: lighten($sidebar-menu-link-bg-color-on-hover, 3%) !default;

// Sidebar for mobile
$mobile-sidebar-menu-bg-color: darken($bg-color, 7%) !default;
$mobile-sidebar-menu-link-bg-color-on-hover: darken($bg-color, 4%) !default;

// Light sidebar menu
$light-sidebar-menu-link-border-color: $brand-main-color !default;
$light-sidebar-menu-link-bg-color-on-hover: lighten($bg-color, 2%) !default;
$light-sidebar-menu-link-bg-color-on-active: lighten($bg-color, 4%) !default;
$light-sidebar-menu-link-font-color-on-active: #f1f1f1 !default;
$light-sidebar-menu-link-icon-color-on-active: #eeeeee !default;
$light-sidebar-menu-link-arrow-color-on-active: #eeeeee !default;

$light-sidebar-menu-sub-menu-bg-color: lighten($bg-color, 2%) !default;
$light-sidebar-menu-sub-menu-link-bg-color-on-hover: lighten($bg-color, 4%) !default;

$mobile-light-sidebar-menu-sub-menu-bg-color: $mobile-sidebar-menu-bg-color !default;
$mobile-light-sidebar-menu-link-bg-color-on-hover: lighten($mobile-sidebar-menu-bg-color, 3%) !default;
$mobile-light-sidebar-menu-link-bg-color-on-active: lighten($mobile-sidebar-menu-bg-color, 3%) !default;
$mobile-light-sidebar-menu-sub-menu-link-bg-color-on-hover: lighten($mobile-sidebar-menu-bg-color, 3%) !default;

// Sidebar search
$sidebar-search-bg-color: darken($bg-color, 5%) !default;
$sidebar-search-bottom-border-color: lighten($sidebar-menu-devider-border-color, 3%) !default;
$sidebar-search-full-border-color: lighten($sidebar-menu-devider-border-color, 3%) !default;
$sidebar-search-input-font-color: lighten($sidebar-menu-devider-border-color, 8%) !default;
$sidebar-search-input-placeholder-font-color: lighten($sidebar-menu-devider-border-color, 8%) !default;

// Quick Sidebar
$quick-sidebar-bg-color: lighten($header-bg-color, 12%);
$quick-sidebar-font-color: #b4bcc8;

// Footer
$footer-default-font-color: lighten($bg-color, 40%) !default;
$footer-default-go-top-bg-color: lighten($bg-color, 7%) !default;
$footer-default-go-top-icon-font-color: lighten($bg-color, 30%) !default;
$footer-fixed-bg-color: darken($bg-color, 7%) !default;

//Boxed layout
$for-min-992px-page-boxed-page-container-bg-color: $sidebar-menu-devider-border-color !default;
$for-min-992px-page-boxed-bg-color: darken($bg-color, 3%) !default;
$for-min-992px-page-boxed-sidebar-fixed-border-color: $sidebar-menu-devider-border-color !default;

//## Base theme color file

/***********
Page Header
***********/

/* Header search bar, toggler button & top menu */
.page-header.navbar {
  background-color: $header-bg-color;

  /* Top notification menu/bar */
  .top-menu {
    .navbar-nav {
      > li.dropdown {
        .dropdown-toggle {
          > i {
            color: $header-top-menu-icon-font-color;
          }

          .badge.badge-default {
            background-color: $header-top-menu-badge-bg-color;
            color: $header-top-menu-badge-font-color;
          }

          &:hover {
            background-color: $header-top-menu-bg-hover-color;

            > i {
              color: lighten($header-top-menu-icon-font-color, 15%);
            }
          }
        }

        &.open {
          .dropdown-toggle {
            background-color: $header-top-menu-bg-hover-color-on-dropdown-open;

            > i {
              color: lighten($header-top-menu-icon-font-color, 15%);
            }
          }
        }
      }

      /* Extended Dropdowns */
      > li.dropdown-extended {

        .dropdown-menu {
          border-color: $header-top-menu-extended-dropdown-border-color;

          &:after {
            border-bottom-color: $header-top-menu-extended-dropdown-header-bg-color;
          }

          > li.external {
            background: $header-top-menu-extended-dropdown-header-bg-color;

            > h3 {
              color: $header-top-menu-extended-dropdown-header-font-color;
            }

            > a {
              color: $link-color;

              &:hover {
                color: $link-hover-color;
                text-decoration: none;
              }
            }
          }

          .dropdown-menu-list {
            > li {
              > a {
                border-bottom: 1px solid $header-top-menu-extended-dropdown-item-border-color !important;
                color: $header-top-menu-extended-dropdown-item-font-color;

                &:hover {
                  background: $header-top-menu-extended-dropdown-item-bg-color-on-hover;
                }
              }
            }
          }
        }
      }

      /* Notification */
      > li.dropdown-notification {
        .dropdown-menu {
          .dropdown-menu-list {
            > li {
              > a {
                .time {
                  background: $header-top-menu-notification-time-bg-color;
                }

                &:hover {
                  .time {
                    background: darken($header-top-menu-notification-time-bg-color, 5%);
                  }
                }
              }
            }
          }
        }
      }

      /* Inbox */
      > li.dropdown-inbox {
        > .dropdown-toggle {
          > .circle {
            background-color: $brand-main-color;
            color: $brand-main-font-color;
          }

          > .corner {
            border-color: transparent transparent transparent $brand-main-color;
          }
        }

        .dropdown-menu {
          .dropdown-menu-list {
            .subject {
              .from {
                color: $header-top-menu-inbox-dropdown-from-font-color;
              }
            }
          }
        }
      }

      /* Tasks */
      > li.dropdown-tasks {

        .dropdown-menu {
          .dropdown-menu-list {
            .progress {
              background-color: $header-top-menu-task-dropdown-progress-bg-color;
            }
          }
        }
      }

      /* User */
      > li.dropdown-user {
        > .dropdown-toggle {

          > .username {
            color: $header-top-menu-user-font-color;
          }

          > i {
            color: $header-top-menu-user-font-color;
          }
        }

        > .dropdown-menu {
          width: 195px;
        }
      }

      /* Language */
      > li.dropdown-language {

        > .dropdown-toggle {
          > .langname {
            color: $header-top-menu-user-font-color;
          }
        }
      }

      /* Dark version */
      > li.dropdown-dark {
        .dropdown-menu {
          background: $header-top-menu-dropdown-dark-bg-color;
          border: 0;

          &:after {
            border-bottom-color: $header-top-menu-dropdown-dark-bg-color;
          }

          > li.external {
            background: $header-top-menu-dropdown-dark-header-bg-color;

            > h3 {
              color: $header-top-menu-dropdown-dark-header-font-color;
            }

            > a {
              &:hover {
                color: lighten($link-color, 11%);
              }
            }
          }

          &.dropdown-menu-default,
          .dropdown-menu-list {
            > li {
              a {
                color: $header-top-menu-dropdown-dark-item-font-color;
                border-bottom: 1px solid $header-top-menu-dropdown-dark-item-border-color !important;

                > i {
                  color: $header-top-menu-dropdown-dark-item-icon-color;
                }

                &:hover {
                  background: $header-top-menu-dropdown-dark-item-bg-color-on-hover;
                }
              }
            }
          }

          &.dropdown-menu-default {
            > li {
              a {
                border-bottom: 0 !important;
              }

              &.divider {
                background: $header-top-menu-dropdown-dark-default-menu-divider;
              }
            }
          }
        }
      }

      > li.dropdown-notification.dropdown-dark {
        .dropdown-menu {
          .dropdown-menu-list {
            > li {
              > a {
                .time {
                  background: $header-top-menu-dropdown-dark-notification-time-bg-color;
                }

                &:hover {
                  .time {
                    background: darken($header-top-menu-dropdown-dark-notification-time-bg-color, 5%);
                  }
                }
              }
            }
          }
        }
      }
    }
  }

  /* Header seaech box */
  .search-form {
    background: $header-search-bg-color;

    &:hover {
      background: $header-search-bg-hover-color;
    }

    .input-group {
      .form-control {
        color: $header-search-font-color;

        @include placeholder($header-search-placeholder-font-color);
      }

      .input-group-btn {
        .btn.submit {
          > i {
            color: $header-search-font-color;
          }
        }
      }
    }

    &.open {
      background: $header-search-bg-color-on-open;
    }
  }
}

/* Default Horizontal Menu */

.page-header.navbar {

  /* Default Mega Menu */
  .hor-menu {
    .navbar-nav {
      /* Mega menu content */
      > li.mega-menu-dropdown {

        > .dropdown-menu {
          box-shadow: $header-hor-menu-box-shadow;

          .mega-menu-content {

            .mega-menu-submenu {

              li {
                > h3 {
                  color: $header-hor-menu-mega-menu-header-font-color;
                }
              }
            }
          }
        }
      }

      /* Classic menu */
      > li {
        > a {
          color: $header-hor-menu-default-link-font-color;

          > i {
            color: $header-hor-menu-default-link-icon-color;
          }
        }

        &.open > a,
        > a:hover {
          color: $header-hor-menu-default-link-font-color-on-hover;
          background: $header-hor-menu-default-link-bg-color-on-hover !important;

          > i {
            color: $header-hor-menu-default-link-icon-color-on-hover;
          }
        }

        &.active,
        &.current {
          > a,
          > a {
            color: $header-hor-menu-default-link-font-color-on-active;
            background: $header-hor-menu-default-link-bg-color-on-active !important;

            > i {
              color: $header-hor-menu-default-link-icon-color;
            }
          }

          .selected {
            border-top: 6px solid $header-hor-menu-default-link-bg-color-on-active;
          }
        }

        .dropdown-menu {
          box-shadow: $header-hor-menu-box-shadow;
          background: $header-hor-menu-dropdown-menu-bg-color;

          li {

            > a {
              color: $header-hor-menu-dropdown-menu-link-font-color;

              > i {
                color: $header-hor-menu-dropdown-menu-link-icon-color;
              }
            }

            &:hover {
              > a {
                color: $header-hor-menu-dropdown-menu-link-font-color-on-hover;
                background: $header-hor-menu-dropdown-menu-link-bg-color-on-hover;

                > i {
                  color: $header-hor-menu-dropdown-menu-link-icon-color-on-hover;
                }
              }
            }

            &.active,
            &.current {
              > a,
              > a:hover {
                color: $header-hor-menu-dropdown-menu-link-font-color-on-active;
                background: $header-hor-menu-dropdown-menu-link-bg-color-on-active;

                > i {
                  color: $header-hor-menu-dropdown-menu-link-icon-color-on-active;
                }
              }
            }

            &.divider {
              background-color: lighten($header-hor-menu-dropdown-menu-bg-color, 5%);
            }
          }
        }

        .dropdown-submenu {
          > a:after {
            color: $header-hor-menu-dropdown-menu-link-icon-color;
          }
        }
      }
    }
  }

  /* Light Mega Menu */
  .hor-menu.hor-menu-light {
    .navbar-nav {
      /* Mega menu content */
      > li.mega-menu-dropdown {

        > .dropdown-menu {
          box-shadow: $header-light-hor-menu-box-shadow;

          .mega-menu-content {

            .mega-menu-submenu {

              li {
                > h3 {
                  color: $header-light-hor-menu-mega-menu-header-font-color;
                }
              }
            }
          }
        }
      }

      /* Classic menu */
      > li {
        > a {
          color: $header-light-hor-menu-default-link-font-color;

          > i {
            color: $header-light-hor-menu-default-link-icon-color;
          }
        }

        > a:hover {
          color: $header-light-hor-menu-default-link-font-color-on-hover;
          background: $header-light-hor-menu-default-link-bg-color-on-hover;

          > i {
            color: $header-light-hor-menu-default-link-icon-color-on-hover;
          }
        }

        &.open > a {
          color: $header-light-hor-menu-default-link-font-color-on-onen !important;
          background: $header-light-hor-menu-default-link-bg-color-on-onen !important;

          > i {
            color: $header-light-hor-menu-default-link-icon-color-on-onen !important;
          }
        }

        &.active,
        &.current {
          > a,
          > a:hover {
            color: $header-light-hor-menu-default-link-font-color-on-active;
            background: $header-light-hor-menu-default-link-bg-color-on-active;

            > i {
              color: $header-light-hor-menu-default-link-icon-color;
            }
          }
        }

        .dropdown-menu {
          box-shadow: $header-light-hor-menu-box-shadow;
          background: $header-light-hor-menu-dropdown-menu-bg-color;

          li {

            > a {
              color: $header-light-hor-menu-dropdown-menu-link-font-color;

              > i {
                color: $header-light-hor-menu-dropdown-menu-link-icon-color;
              }
            }

            &:hover {
              > a {
                color: $header-light-hor-menu-dropdown-menu-link-font-color-on-hover;
                background: $header-light-hor-menu-dropdown-menu-link-bg-color-on-hover;

                > i {
                  color: $header-light-hor-menu-dropdown-menu-link-icon-color-on-hover;
                }
              }
            }

            &.active,
            &.current {
              > a,
              > a:hover {
                color: $header-light-hor-menu-dropdown-menu-link-font-color-on-active;
                background: $header-light-hor-menu-dropdown-menu-link-bg-color-on-active;

                > i {
                  color: $header-light-hor-menu-dropdown-menu-link-icon-color-on-active;
                }
              }
            }

            &.divider {
              background-color: darken($header-light-hor-menu-dropdown-menu-bg-color, 4%);
            }
          }
        }

        .dropdown-menu {
          border: 1px solid darken($header-light-hor-menu-default-link-bg-color-on-onen, 5%);
        }

        > .dropdown-menu {
          border-top: 0;
        }
      }
    }
  }
}

/* Page sidebar */

.page-sidebar-closed.page-sidebar-fixed .page-sidebar:hover,
.page-sidebar {
  background-color: $bg-color;

  /* Default sidebar */
  .page-sidebar-menu {

    /* 1st level links */

    > li {
      > a {
        border-top: 1px solid $sidebar-menu-devider-border-color;
        color: $sidebar-menu-link-font-color;

        > i {
          color: $sidebar-menu-link-icon-font-color;
        }

        > i[class^="icon-"],
        > i[class*="icon-"] {
          @if $theme-name == "light" {
            color: darken($sidebar-menu-link-icon-font-color, 15%);
          } @else if $theme-name == "light2" {
            color: darken($sidebar-menu-link-icon-font-color, 15%);
          } @else {
            color: lighten($sidebar-menu-link-icon-font-color, 5%);
          }
        }

        > .arrow {
          &:before,
          &.open:before {
            color: $sidebar-menu-arrow-color;
          }
        }
      }

      &.heading {
        > h3 {
          color: darken($sidebar-menu-link-font-color, 23%);
        }
      }

      &:hover,
      &.open {
        > a {
          background: $sidebar-menu-link-bg-color-on-hover;
          color: $sidebar-menu-link-font-color-on-hover;

          > i {
            color: $sidebar-menu-link-icon-font-color-on-hover;
          }

          > .arrow {
            &:before,
            &.open:before {
              color: $sidebar-menu-arrow-color-on-hover;
            }
          }
        }
      }

      &.active,
      &.active.open {
        > a {
          background: $sidebar-menu-link-bg-color-on-active;
          border-top-color: transparent;
          color: $sidebar-menu-link-font-color-on-active;

          &:hover {
            background: $sidebar-menu-link-bg-color-on-active;
          }

          > i {
            color: $sidebar-menu-link-icon-font-color-on-active;
          }

          > .arrow {
            &:before,
            &.open:before {
              color: $sidebar-menu-arrow-color-on-active;
            }
          }
        }
      }

      &.active + li {
        > a {
          border-top-color: transparent;
        }
      }

      &.active.open + li {
        > a {
          border-top-color: $sidebar-menu-devider-border-color;
        }
      }

      &:last-child {
        > a {
          border-bottom: 1px solid transparent !important;
        }
      }
    }

    /* All links */

    li {
      > a {
        > .arrow {
          &:before,
          &.open:before {
            color: $sidebar-menu-arrow-color;
          }
        }
      }

      &:hover {
        > a {
          > .arrow {
            &:before,
            &.open:before {
              color: $sidebar-menu-arrow-color-on-hover;
            }
          }
        }
      }

      &.active {
        > a {
          > .arrow {
            &:before,
            &.open:before {
              color: $sidebar-menu-arrow-color-on-active;
            }
          }
        }
      }
    }

    .page-sidebar-closed &:hover {
      .sub-menu {
        background-color: $bg-color;
      }
    }

    .sub-menu {
      > li {
        > a {
          color: $sidebar-menu-sub-menu-link-font-color;

          > i {
            color: $sidebar-menu-sub-menu-link-icon-font-color;
          }

          > i[class^="icon-"],
          > i[class*="icon-"] {
            @if $theme-name == "light" {
              color: darken($sidebar-menu-link-icon-font-color, 15%);
            } @else if $theme-name == "light2" {
              color: darken($sidebar-menu-link-icon-font-color, 15%);
            } @else {
              color: lighten($sidebar-menu-link-icon-font-color, 5%);
            }
          }

          > .arrow {
            &:before,
            &.open:before {
              color: $sidebar-menu-arrow-color;
            }
          }
        }

        &:hover,
        &.open,
        &.active {
          > a {
            background: $sidebar-menu-sub-menu-link-bg-color-on-hover !important;

            > i {
              color: $sidebar-menu-sub-menu-link-icon-font-color-on-hover;
              @if $theme-name == "light" {
                color: darken($sidebar-menu-link-icon-font-color, 15%);
              } @else if $theme-name == "light2" {
                color: darken($sidebar-menu-link-icon-font-color, 15%);
              } @else {
                color: lighten($sidebar-menu-link-icon-font-color, 20%);
              }
            }

            > .arrow {
              &:before,
              &.open:before {
                color: $sidebar-menu-arrow-color-on-hover;
              }
            }
          }
        }
      }
    }
  }

  /* light sidebar */
  .page-sidebar-menu.page-sidebar-menu-light {

    /* 1st level links */
    > li {
      &:hover,
      &.open {
        > a {
          background: $light-sidebar-menu-link-bg-color-on-hover;
        }
      }

      &.active,
      &.active.open {
        > a {
          background: $light-sidebar-menu-link-bg-color-on-active;
          border-left: 4px solid $light-sidebar-menu-link-border-color;
          color: $light-sidebar-menu-link-font-color-on-active;

          &:hover {
            border-left: 4px solid $sidebar-menu-link-bg-color-on-active;
            background: $light-sidebar-menu-link-bg-color-on-hover;
          }

          > i {
            color: $light-sidebar-menu-link-icon-color-on-active;
          }

          > .arrow {
            &:before,
            &.open:before {
              color: $light-sidebar-menu-link-arrow-color-on-active;
            }
          }
        }
      }

      .sub-menu {
        background: $light-sidebar-menu-sub-menu-bg-color;

        > li {
          &:hover,
          &.open,
          &.active {
            > a {
              background: $light-sidebar-menu-sub-menu-link-bg-color-on-hover !important;
            }
          }
        }
      }
    }
  }

  /* Sidebar search */

  .sidebar-search {

    .input-group {
      border-bottom: 1px solid $sidebar-search-bottom-border-color;

      .form-control {
        background-color: $bg-color;
        color: $sidebar-search-input-font-color;
        @include placeholder($sidebar-search-input-placeholder-font-color);
      }

      .input-group-btn {
        .btn {
          > i {
            color: $sidebar-search-input-font-color;
          }
        }
      }
    }

    &.sidebar-search-bordered {
      .input-group {
        border: 1px solid $sidebar-search-full-border-color;
      }
    }

    .page-sidebar-closed &.open {
      .input-group {
        background-color: $bg-color;
      }

      .remove {
        > i {
          color: $sidebar-search-input-font-color;
        }
      }
    }

    &.sidebar-search-solid {

      .page-sidebar-closed & {
        .input-group {
          background: none;
        }
      }

      .input-group {
        border: 1px solid $sidebar-search-bg-color;
        background: $sidebar-search-bg-color;

        .form-control {
          background: $sidebar-search-bg-color;
        }
      }

      &.open .input-group {
        border: 1px solid $bg-color;
        background: $bg-color;

        .form-control {
          background: $bg-color;
        }
      }
    }
  }
}

.page-sidebar-reversed {

  .page-sidebar-menu.page-sidebar-menu-light {
    /* 1st level links */
    > li {
      &.active,
      &.active.open {
        > a {
          border-left: 0;
          border-right: 4px solid $light-sidebar-menu-link-border-color;

          &:hover {
            border-left: 0;
            border-right: 4px solid $sidebar-menu-link-bg-color-on-active;
          }
        }
      }
    }
  }
}

/*************
Quick Sidebar
*************/

/***
Quick Sidebar Layout
***/

.page-quick-sidebar-wrapper {
  background: $quick-sidebar-bg-color;

  .page-quick-sidebar {
    background: $quick-sidebar-bg-color;
  }
}

/***
Quick Sidebar Toggler
***/

.page-quick-sidebar-toggler {
  background: lighten($quick-sidebar-bg-color, 10%);

  &:hover {
    background: darken(lighten($quick-sidebar-bg-color, 10%), 3%);
  }

  > i {
    color: lighten($quick-sidebar-font-color, 10%);
  }
}

/***
Quick Sidebar Content
***/

.page-quick-sidebar-wrapper {
  color: lighten($quick-sidebar-font-color, 10%);

  .page-quick-sidebar {

    /* Quick sidebar tabs */
    .nav-justified {
      > li {

        > a {
          color: lighten($quick-sidebar-font-color, 7%);
          background: lighten($quick-sidebar-bg-color, 10%);

          &:hover {
            background: lighten($quick-sidebar-bg-color, 5%);
          }
        }

        &.open {
          > a {
            color: lighten($quick-sidebar-font-color, 7%);
            background: lighten($quick-sidebar-bg-color, 10%);
          }
        }

        &.active {
          > a {
            border: 0;
            background: $quick-sidebar-bg-color;
          }
        }

        .dropdown-menu {
          border: 0;
          background: lighten($quick-sidebar-bg-color, 10%);
          box-shadow: 5px 5px rgba(lighten($quick-sidebar-bg-color, 30%), 0.1);

          &:before {
            border-bottom: 7px solid lighten($quick-sidebar-bg-color, 10%);
          }

          &:after {
            border-bottom: 7px solid lighten($quick-sidebar-bg-color, 10%);
          }

          > li {
            > a {
              color: lighten($quick-sidebar-font-color, 10%);

              > i {
                color: lighten($quick-sidebar-font-color, 8%);
              }

              &:hover {
                background: lighten($quick-sidebar-bg-color, 13%);
                color: lighten($quick-sidebar-font-color, 10%);

                > i {
                  color: lighten($quick-sidebar-font-color, 11%);
                }
              }
            }

            &.active {
              > a {
                background: lighten($quick-sidebar-bg-color, 11%);
                color: lighten($quick-sidebar-font-color, 10%);
              }
            }

            &.divider {
              background-color: lighten($quick-sidebar-bg-color, 13%);
            }
          }
        }
      }
    }

    /* Quick sidebar general list heading */
    .list-heading {
      color: darken($quick-sidebar-font-color, 5%);
    }

    /* Quick sidebar general list-items */
    .list-items {
      margin: 0;
      padding: 0;
      list-style: none;

      > li {
        border-bottom-color: lighten($quick-sidebar-bg-color, 3%);

        &:hover {
          background: lighten($quick-sidebar-bg-color, 3%);
        }
      }
    }
  }

  .page-quick-sidebar-item {

    /* back to list */
    .page-quick-sidebar-nav {
      .page-quick-sidebar-back-to-list {
        color: lighten($quick-sidebar-font-color, 7%);
      }
    }
  }

  /* Quick sidebar chat */
  .page-quick-sidebar-chat {

    // chat users
    .page-quick-sidebar-chat-users {
      .media-list {
        .media {
          .media-body {
            .media-heading-sub {
              color: darken($quick-sidebar-font-color, 8%);
            }

            .media-heading-small {
              color: darken($quick-sidebar-font-color, 12%);
            }
          }
        }
      }
    }

    // user chat
    .page-quick-sidebar-chat-user {
      .page-quick-sidebar-chat-user-messages {
        .post {
          .name {
            color: lighten($quick-sidebar-font-color, 3%);
          }

          .datetime {
            color: lighten($quick-sidebar-font-color, 3%);
          }

          .message {
            color: lighten($quick-sidebar-font-color, 7%);
            background: lighten($quick-sidebar-bg-color, 10%);
          }

          &.in {
            .message {
              .arrow {
                border-right-color: lighten($quick-sidebar-bg-color, 10%);
              }
            }
          }

          &.out {
            .message {
              .arrow {
                border-left-color: lighten($quick-sidebar-bg-color, 10%);
              }
            }
          }
        }
      }
    }
  }

  /* Quick sidebar alerts */

  .page-quick-sidebar-alerts {
    .page-quick-sidebar-alerts-list {
      .feeds {
        li {
          a {
            color: lighten($quick-sidebar-font-color, 1%);

            .desc {
              text-decoration: underline;
            }
          }

          .desc {
            color: darken($quick-sidebar-font-color, 1%);
          }

          .date {
            color: darken($quick-sidebar-font-color, 12%);
          }
        }
      }
    }
  }
}

/******
Page Footer
******/

.page-footer {
  .page-footer-inner {
    color: $footer-default-font-color;
  }

  .page-footer-fixed & {
    background-color: $footer-fixed-bg-color;
  }
}

@media (min-width: $screen-md-min) {
  /* 992px */

  /* Sidebar menu closed */
  .page-sidebar-menu.page-sidebar-menu-hover-submenu {
    > li:hover {
      > .sub-menu {
        box-shadow: 5px 5px rgba($sidebar-menu-sub-menu-box-shadow-color, 0.2);

        &.sidebar-toggler-wrapper,
        &.sidebar-search-wrapper {
          box-shadow: none;
        }
      }
    }
  }

  .page-sidebar-menu.page-sidebar-menu-closed {
    > li:hover {
      box-shadow: 5px 5px rgba($sidebar-menu-sub-menu-box-shadow-color, 0.2);

      &.sidebar-toggler-wrapper,
      &.sidebar-search-wrapper {
        box-shadow: none;
      }

      > .sub-menu {
        box-shadow: 5px 5px rgba($sidebar-menu-sub-menu-box-shadow-color, 0.2);

        &.sidebar-toggler-wrapper,
        &.sidebar-search-wrapper {
          box-shadow: none;
        }
      }
    }
  }

  /* Light sidebar menu */
  .page-sidebar-menu.page-sidebar-menu-light.page-sidebar-menu-closed {
    > li.heading {
      padding: 0;
      margin-top: 15px;
      margin-bottom: 15px;
      border-top: 1px solid $sidebar-menu-devider-border-color !important;
    }
  }

  /* Fixed Sidebar */

  .page-sidebar-fixed:not(.page-footer-fixed) {
    .page-content {
      border-bottom: 0;
    }

    .page-footer {
      background-color: #fff;

      .page-footer-inner {
        color: #333;
      }
    }
  }

  /* Boxed Layout */

  .page-boxed {
    background-color: $for-min-992px-page-boxed-bg-color !important;

    /* Page container */
    .page-container {
      background-color: $bg-color;
      border-left: 1px solid $for-min-992px-page-boxed-page-container-bg-color;
      border-bottom: 1px solid $for-min-992px-page-boxed-page-container-bg-color;
    }

    &.page-sidebar-reversed {
      .page-container {
        border-left: 0;
        border-right: 1px solid $for-min-992px-page-boxed-page-container-bg-color;
      }
    }

    &.page-sidebar-fixed {
      .page-container {
        border-left: 0;
        border-bottom: 0;
      }
    }

    &.page-sidebar-reversed.page-sidebar-fixed {
      .page-container {
        border-left: 0;
        border-right: 0;
        border-bottom: 0;
      }
    }

    /* Page sidebar */

    &.page-sidebar-fixed {
      .page-sidebar {
        border-left: 1px solid $for-min-992px-page-boxed-sidebar-fixed-border-color;
      }
    }

    &.page-sidebar-reversed.page-sidebar-fixed {
      .page-sidebar {
        border-right: 1px solid $for-min-992px-page-boxed-sidebar-fixed-border-color;
        border-left: 0;
      }
    }

    /* Page footer */

    &.page-sidebar-fixed.page-footer-fixed {
      .page-footer {
        background-color: $for-min-992px-page-boxed-bg-color !important;

        .page-footer-inner {
          color: $footer-default-font-color;
        }
      }
    }
  }

  /* Sidebar Menu Wirh Hoverable Submenu */

  .page-sidebar-menu-hover-submenu {
    li {
      &:hover {
        a {
          > .arrow {
            border-right: 8px solid $sidebar-menu-hover-sub-menu-bg-color;

            .page-sidebar-reversed & {
              border-left: 8px solid $sidebar-menu-hover-sub-menu-bg-color;
            }
          }
        }

        > .sub-menu {
          background: $sidebar-menu-hover-sub-menu-bg-color !important;
        }
      }
    }
  }
}

@media (max-width: $screen-sm-max) {
  /* 991px */
  /* Page sidebar */
  .page-sidebar {
    background-color: $mobile-sidebar-menu-bg-color;

    .page-sidebar-menu {
      > li {
        > a {
          border-top: 1px solid $bg-color;
        }

        &:hover,
        &.open {
          > a {
            background: $mobile-sidebar-menu-link-bg-color-on-hover;
          }
        }

        &:last-child {
          > a {
            border-bottom: 0 !important;
          }
        }

        .sub-menu {
          background-color: $mobile-sidebar-menu-bg-color !important;
        }
      }

      .sidebar-search {
        input {
          background-color: $mobile-sidebar-menu-bg-color !important;
        }
      }
    }

    /* light sidebar */
    .page-sidebar-menu.page-sidebar-menu-light {

      /* 1st level links */
      > li {
        &:hover,
        &.open {
          > a {
            background: $mobile-light-sidebar-menu-link-bg-color-on-hover;
          }
        }

        &.active,
        &.active.open {
          > a {
            background: $mobile-light-sidebar-menu-link-bg-color-on-active;

            &:hover {
              background: $mobile-light-sidebar-menu-link-bg-color-on-active;
            }
          }
        }

        .sub-menu {
          background: $mobile-light-sidebar-menu-sub-menu-bg-color !important;

          > li {
            &:hover,
            &.open,
            &.active {
              > a {
                background: $mobile-light-sidebar-menu-sub-menu-link-bg-color-on-hover !important;
              }
            }
          }
        }
      }
    }
  }
}

@media (max-width: $screen-xs-min) {
  /* 480px */

  .page-header.navbar {
    /* Top menu */
    .top-menu {
      background-color: $bg-color;

      .page-header-fixed-mobile & {
        background-color: $header-bg-color;
      }

      .navbar-nav {
        > li.dropdown-user {
          .dropdown-toggle {
            background-color: lighten($header-top-menu-bg-hover-color, 1%);

            .page-header-fixed-mobile & {
              background: none;
            }

            &:hover {
              background-color: $header-top-menu-bg-hover-color;
            }
          }
        }
      }
    }
  }
}

/****
Boby
****/

body {
  background-color: $bg-color;
}

/****
 CSS3 Spinner Bar
****/
@import "loaders";
.page-spinner-bar > div,
.block-spinner-bar > div {
  background: lighten($brand-main-color, 5%);
}
