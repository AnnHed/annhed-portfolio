<div class="wrapper">
    <div class="box header">Header</div>
    <div class="box sidebar">Sidebar</div>
    <div class="box content">Content</div>
</div>

<div class="wrapper">
  <div>One</div>
  <div>Two</div>
  <div>Three</div>
  <div>Four</div>
  <div>Five</div>
</div>

/* Code before last attempt 11 dec late at night */

.sidebar {
    grid-column: col;
    grid-row: row 2 ;
}

.content {
    grid-column: col 2 / span  3;
    grid-row: row 2;
}

.image {
    grid-column: col / span 2;
    grid-row: row 3;
}

.funny {
    grid-column: col 3 / span 2 ;
    grid-row: row ;
}

<!-- <p>&nbsp;</p> -->

<!-- //    @include breakpoint(papa-bear) { width: 60%; }
//    @include breakpoint(mama-bear) { width: 80%; }
//    @include breakpoint(baby-bear) { width: 95%; } -->
