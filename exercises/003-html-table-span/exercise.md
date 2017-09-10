# Description

This is another exercise for the HTML advanced lesson. You'll need to remember what the basic HTML structure looks like, how to use tables and the "colspan" and "rowspan" attributes.

# Tasks

1. Create a basic HTML page layout, with all important elements.

2. Create the following table using the "colspan" attribute.

<table>
    <thead>
        <tr>
            <th>Name</th>
            <th colspan="2">Phone</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td>Peter Shaw</td>
            <td>0123 456 300</td>
            <td>0123 456 400</td>
        </tr>
        <tr>
            <td>Bob Andrews</td>
            <td>0123 456 500</td>
            <td>0123 456 600</td>
        </tr>
    </tbody>
</table>

3. Create the following table using the "rowspan" attribute.

<table>
    <tr>
        <th>Name:</th>
        <td>Max Goldwell</td>
    </tr>
    <tr>
        <th rowspan="3" valign="top">Phone:</th>
        <td>0123 456 400</td>
    </tr>
    <tr>
        <td>0123 456 600</td>
    </tr>
    <tr>
        <td>0123 456 800</td>
    </tr>
</table>