<template>
  <div id="app">
    <strong><h1>2021/1st Schedule</h1></strong>
    <center>
      <Subject
        subName="Soft Specification and Design"
        teacherName="กฤษณะ ไวยมัย"
        day="MON"
        startTime="13"
        endTime="15"
        note="Classroom"
        work=""
        style="background-color: #f7cd53;"
      />

      <Subject
        subName="Database Systems for Software and Knowledge Engineers"
        teacherName="กฤษณะ ไวยมัย"
        day="TUE"
        startTime="13"
        endTime="16"
        note=""
        work=""
        style="background-color: #de6e7b;"
      />
      <Subject
        subName="Introduction to Computer Systems"
        teacherName="ภารุจ รัตนวรพันธุ์"
        day="TUE"
        startTime="16"
        endTime="17.30"
        note="Classroom"
        work=""
        style="background-color: #de6e7b;"
      />

      <Subject
        subName="Computer System Laboratory"
        teacherName="ภารุจ รัตนวรพันธุ์"
        day="WED"
        startTime="9"
        endTime="12"
        note="Classroom"
        work=""
        style="background-color: #20c997;"
      />
      <Subject
        subName="General Physics II"
        teacherName="ชัชวาล วงศ์ชูสุข, ภุชงค์ กิจอำนาจสุข"
        day="WED"
        startTime="13"
        endTime="16"
        note="Classroom"
        work=""
        style="background-color: #20c997;"
      />

      <Subject
        subName="Data Structure and Algorithm II"
        teacherName="ธนาวินท์ รักธรรมานนท์"
        day="THU"
        startTime="13"
        endTime="15"
        note="Classroom"
        work=""
        style="background-color: orange"
      />
      <Subject
        subName="Introduction to Computer Systems"
        teacherName="ภารุจ รัตนวรพันธุ์"
        day="THU"
        startTime="13"
        endTime="15"
        note="Classroom"
        work=""
        style="background-color: orange"
      />

      <Subject
        subName="Knowledge Engineering and Knowledge Management I"
        teacherName="หัชทัย ชาญเลขา"
        day="FRI"
        startTime="9"
        endTime="12"
        note="Classroom"
        work=""
        style="background-color: #3e64ff"
      />
      <Subject
        subName="Software Specification and Design"
        teacherName="กฤษณะ ไวยมัย"
        day="FRI"
        startTime="13"
        endTime="16"
        note="Classroom"
        work=""
        style="background-color: #3e64ff"
      />
    </center>
  </div>
</template>

<script>
import Subject from "./components/Subject.vue";

export default {
  name: "App",
  components: {
    Subject,
  },
};
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
