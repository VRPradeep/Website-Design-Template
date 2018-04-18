<template>
  <div style="width: 1400px; max-width: 700vw;">
  <div class="layout-padding">
    <div class="text-right">
      <h6>Welcome to Dr.Xueping Li's Website!</h6>
      <h6> Work <em>HARD!</em> Play <em>HARD!!</em> </h6>
    </div>

    <q-tabs slot="navigation" v-if="true" color="orange-7" >
      <q-route-tab slot="title"  to="/home" replace label="Home" class="text-bold"/>
      <q-route-tab slot="title"  to="/publication" replace label="Publication" class="text-bold" />
      <!-- <q-route-tab slot="title"  to="/research" replace label="Research" /> -->
      <q-route-tab slot="title"  to="/teaching" replace label="Teaching" />
      <q-route-tab slot="title"  to="/services" replace label="Services" />
      <!-- <q-route-tab slot="title"  to="/students" replace label="Students" /> -->
      <q-route-tab slot="title"  to="/resources" replace label="Resources" />
      <q-route-tab slot="title"  to="/studentsduplicate" replace label="Students Duplicate" />
      <q-route-tab slot="title"  to="/researchduplicate" replace label="Research Duplicate" />
      <q-route-tab slot="title"  to="/publicationduplicate" replace label="Publication Duplicate" />
      </q-tabs>
      <router-view />
    </div>
      <!--
      <img src="~assets/Li.jpg" class="responsive" align="center" style="width:200px;height:200px;">
    </br> -->
      <!--<div>
        <h2 >Xueping Li</h2>
        <p>Xueping Li is an is <em>Associate Professor</em> an Associate Professor of Industrial and Systems Engineering and the Director of the iLab (Ideation Laboratory) and Co-Director of the HITS (Health Information Technology and Simulation) Lab at the University of Tennessee - Knoxville. He holds a Ph.D. from Arizona State University. His research areas include health systems engineering, information assurance, scheduling, web mining, supply chain management, lean manufacturing and sensor networks. He is a member of IIE, IEEE and INFORMS.</p>
      </div> -->
      <!-- </q-card-main> -->
</div>
</template>
