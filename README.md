jatis-express
=============

jatis express front-end

How to use:

Tambah dependency baru:
<!-- Dependency for zhtml -->
<dependency>
    <groupId>org.zkoss.zk</groupId>
    <artifactId>zhtml</artifactId>
    <version>${zkoss.version}</version>
</dependency>

Layout
---------------------------------------------------------------------------------
HEADER <include src="Inc_Header.zul">
---------------------------------------------------------------------------------

                              .container-fluid
   __________________________________________________________________________
   |LEFTMENU                           | MAIN-CONTENT .main                  |
   |<include src="Inc_LeftMenu.zul">   | SUB-CONTENT  .row                   |
   |                                   |                                     |
   |                                   |                                     |
   ---------------------------------------------------------------------------

---------------------------------------------------------------------------------

Komponen layout

     <!--  start pool -->  
     <div sclass="control-group">
        <label sclass="control-label span2" value="Pool"/>
 	<combobox>
	   <comboitem label="1"/>
	   <comboitem label="2"/>
	   <comboitem label="3"/>
	</combobox>
     </div>
     <!--  end pool -->

Penjelasan:
1. Komponen terletak di dalam DIV dengan class .control-group
2. setiap komponen akan rata-kiri (float left)


ZK Komponen yang sudah di style (Override default style):
1. textbox (Position and width non-overide) dapat menggunakan class di bawah ini:
        .span1 to .span12       For width size
        .pull-right             float right
        .pull-left              float left
2. tree 
3. Grid
4. Listbox  (Position and width non-overide) dapat menggunakan class di bawah ini:
        .span1 to .span12       For width size
        .pull-right             float right
        .pull-left              float left
5. Combobox  (Position and width non-overide) dapat menggunakan class di bawah ini:
        .span1 to .span12       For width size
        .pull-right             float right
        .pull-left              float left
6. Button (non-override, bisa langsung gunakan class) seperti di bawah ini:
	.btn 	                Standard gray button with gradient
	.btn btn-primary 	Provides extra visual weight and identifies the primary action in a set of buttons
	.btn btn-info 	        Used as an alternative to the default styles
	.btn btn-success 	Indicates a successful or positive action
	.btn btn-warning 	Indicates caution should be taken with this action
	.btn btn-danger 	Indicates a dangerous or potentially negative action
	.btn btn-inverse 	Alternate dark gray button, not tied to a semantic action or use
	.btn btn-link           Deemphasize a button by making it look like a link while maintaining button behavior

        .btn-large              Large size button
        .btn-small              Small button
        .btn-mini               mini button
7. Datebox

XHTML Component:
Automatically styled


Penggunaan Icons dengan XHTML: Ref http://twitter.github.io/bootstrap/base-css.html#icons

NORMAL HTML TAG:
<i class="icon-glass"></i> (posisi tergantung di mana peletakan tag)

ZHTML TAG:
<x:i sclass="icon-glass"></x:i> (posisi selalu di kanan. wtf zk?)

icon-glass
icon-music
icon-search
icon-envelope
icon-heart
icon-star
icon-star-empty
icon-user
icon-film
icon-th-large
icon-th
icon-th-list
icon-ok
icon-remove
icon-zoom-in
icon-zoom-out
icon-off
icon-signal
icon-cog
icon-trash
icon-home
icon-file
icon-time
icon-road
icon-download-alt
icon-download
icon-upload
icon-inbox
icon-play-circle
icon-repeat
icon-refresh
icon-list-alt
icon-lock
icon-flag
icon-headphones
icon-volume-off
icon-volume-down
icon-volume-up
icon-qrcode
icon-barcode
icon-tag
icon-tags
icon-book
icon-bookmark
icon-print
icon-camera
icon-font
icon-bold
icon-italic
icon-text-height
icon-text-width
icon-align-left
icon-align-center
icon-align-right
icon-align-justify
icon-list
icon-indent-left
icon-indent-right
icon-facetime-video
icon-picture
icon-pencil
icon-map-marker
icon-adjust
icon-tint
icon-edit
icon-share
icon-check
icon-move
icon-step-backward
icon-fast-backward
icon-backward
icon-play
icon-pause
icon-stop
icon-forward
icon-fast-forward
icon-step-forward
icon-eject
icon-chevron-left
icon-chevron-right
icon-plus-sign
icon-minus-sign
icon-remove-sign
icon-ok-sign
icon-question-sign
icon-info-sign
icon-screenshot
icon-remove-circle
icon-ok-circle
icon-ban-circle
icon-arrow-left
icon-arrow-right
icon-arrow-up
icon-arrow-down
icon-share-alt
icon-resize-full
icon-resize-small
icon-plus
icon-minus
icon-asterisk
icon-exclamation-sign
icon-gift
icon-leaf
icon-fire
icon-eye-open
icon-eye-close
icon-warning-sign
icon-plane
icon-calendar
icon-random
icon-comment
icon-magnet
icon-chevron-up
icon-chevron-down
icon-retweet
icon-shopping-cart
icon-folder-close
icon-folder-open
icon-resize-vertical
icon-resize-horizontal
icon-hdd
icon-bullhorn
icon-bell
icon-certificate
icon-thumbs-up
icon-thumbs-down
icon-hand-right
icon-hand-left
icon-hand-up
icon-hand-down
icon-circle-arrow-right
icon-circle-arrow-left
icon-circle-arrow-up
icon-circle-arrow-down
icon-globe
icon-wrench
icon-tasks
icon-filter
icon-briefcase
icon-fullscreen
