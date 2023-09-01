---
toc: true
comments: true
layout: post
title: JS Output jquery personalized
type: hacks
courses: { compsci: {week: 2} }
---

%%html

<!-- Head contains information to Support the Document -->
<head>
    <!-- load jQuery and DataTables output style and scripts -->
    <link rel="stylesheet" type="text/css" href="https://cdn.datatables.net/1.13.4/css/jquery.dataTables.min.css">
    <script type="text/javascript" language="javascript" src="https://code.jquery.com/jquery-3.6.0.min.js"></script>
    <script>var define = null;</script>
    <script type="text/javascript" language="javascript" src="https://cdn.datatables.net/1.13.4/js/jquery.dataTables.min.js"></script>
</head>

<!-- Body contains the contents of the Document -->
<body>
    <table id="demo" class="table">
        <thead>
            <tr>
                <th>Title</th>
                <th>Artist</th>
                <th>Year</th>
                <th>Album</th>
                <th>Genre</th>
            </tr>
        </thead>
        <tbody>
            <tr>
                <td>Party Monster</td>
                <td>Weeknd</td>
                <td>2016</td>
                <td>Starboy</td>
                <td>Trap Music</td>
            </tr>
            <tr>
                <td>Telekinesis</td>
                <td>Travis Scott</td>
                <td>2023</td>
                <td>Utopia</td>
                <td>R&B</td>
            </tr>
            <tr>
                <td>Late Night Talking</td>
                <td>Harry Styles</td>
                <td>2022</td>
                <td>Harry's House</td>
                <td>Pop</td>
            </tr>
            <tr>
                <td>Shake It Off</td>
                <td>Taylor Swift</td>
                <td>2014</td>
                <td>1989</td>
                <td>Pop</td>
            </tr>
            <tr>
                <td>Careless Whisper</td>
                <td>George Michael</td>
                <td>1984</td>
                <td>Make it Big</td>
                <td>Pop</td>
            </tr>
            <tr>
                <td>Woofer</td>
                <td>Dr. Zeus</td>
                <td>2018</td>
                <td>Global Injection</td>
                <td>Rap</td>
            </tr>
            <tr>
                <td>Mercy</td>
                <td>Shawn Mendes</td>
                <td>2016</td>
                <td>Illuminate</td>
                <td>R&B</td>
            </tr>
            <tr>
                <td>Thinking out Loud</td>
                <td>Ed Sheeran</td>
                <td>2014</td>
                <td>X</td>
                <td>Soft Rock</td>
            </tr>
            <tr>
                <td>Vulnerable</td>
                <td>Dhruv</td>
                <td>2022</td>
                <td>rapunzel</td>
                <td>Hip Hop</td>
            </tr>
            <tr>
                <td>Good Days</td>
                <td>SZA</td>
                <td>2020</td>
                <td>SOS</td>
                <td>R&B</td>
            </tr>
            <tr>
                <td>Rich Flex</td>
                <td>Drake</td>
                <td>2022</td>
                <td>Her loss</td>
                <td>Rap</td>
            </tr>
        </tbody>
    </table>
</body>

<!-- Script is used to embed executable code -->
<script>
    $("#demo").DataTable();
</script>