<template>
    <div id="rcorners">
        <table>
            <tr>
                <th id="day"><h2>{{ day }}</h2></th>
                <th id="subjectName"><h4>{{ subName }}</h4></th>
                <th id="teacherName"><h4>{{ teacherName }}</h4></th>
                <th id="startTime"><h4>Start: {{ startTime }}</h4></th>
                <th id="endTime"><h4>End: {{ endTime }}</h4></th>
            </tr>
        </table>
        <table>
            <tr>
                <th id="note"><h4>NOTE: {{ note }}</h4></th>
                <th id="work"><h4>WORK: {{ work }}</h4></th>
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
        border-radius: 15px;
        border: 3px solid orangered;
        padding: 3px; 
        background-color: #f7cd53;
        max-width: 75%;
    }
</style>

<script>
export default {
    name: "Subject",
    props:{
        subName: String,
        teacherName: String,
        day: String,
        startTime: Number,
        endTime: Number,
        note: String,
        work: String
    }
}
</script>