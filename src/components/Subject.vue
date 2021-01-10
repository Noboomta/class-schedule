<template>
    <div id="rcorners">
        <table>
            <tr>
                <th id="day"><h3>DAY: {{ day }}</h3></th>
                <th id="subjectName"><h3>NAME: {{ subName }}</h3></th>
                <th id="teacherName"><h3>BY: {{ teacherName }}</h3></th>
                <th id="startTime"><h3>Start: {{ startTime }}</h3></th>
                <th id="endTime"><h3>End: {{ endTime }}</h3></th>
            </tr>
        </table>
        <table>
            <tr>
                <th id="note"><h3>NOTE: {{ note }}</h3></th>
                <th id="work"><h3>WORK: {{ work }}</h3></th>
            </tr>
        </table>
    </div>
</template>

<style>
    table {
        font-family: arial, sans-serif;
        border-collapse: collapse;
        width: 80%;
    }
    td, th {
        /* border: 2px solid #5DADE2; */
        text-align: left;
        padding: 5px;
    }
    #rcorners {
        border-radius: 25px;
        border: 2px solid orangered;
        padding: 10px; 
        background-color: orange;
    }
</style>

<script>
export default {
    name: "Subject",
    props:{
        subName: String,
        teacherName: String,
        day: Number,
        startTime: Number,
        endTime: Number,
        note: String,
        work: String
    }
}
</script>