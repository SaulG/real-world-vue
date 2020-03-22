<template>
    <div class="icon-wrapper">
	<svg class='icon'  :width="width" :height="height">
            <use v-bind="{'xlink:href':'/feather-sprite.svg#'+name}"/>
	</svg>
	<slot></slot> // newly added slot
    </div>
</template>
