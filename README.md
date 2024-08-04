```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>
<body>
    <table>
        <tr>
            <th>First name</th>
            <th> Last name</th>
            <th>Gender</th>

        </tr>

        <tr>
            <td>Murali Naik</td>
            <td> Bukke</td>
            <td>Male</td>
        </tr>

        <tr>
            <td>xxxx</td>
            <td> xxxx</td>
            <td>Female</td>
        </tr>

        <tr>
            <td>xxxx</td>
            <td> xxxx</td>
            <td>Son</td>
        </tr>

        <tr>
            <td>xxxx</td>
            <td> xxxx</td>
            <td>daughter</td>
        </tr>

    </table>
    
</body>
</html>



<style>
    table{
        width: 600px;
        
    }
    table,th,td {
        border: 1px solid;
        border-collapse: collapse;
    }

    th,td{
        padding: 10px;

    }

    th {
        text-align: center;
    }

    tr:nth-child(even){
        background-color: cadetblue;

    }

    tr:nth-child(odd){
        background-color: darkgray;
    }

</style>

```
