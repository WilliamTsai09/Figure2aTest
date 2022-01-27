# Figure2aTest
Figure 2a from raw data
<!doctype>
<script src="../vendor/d3.min.js"></script>
<script src="../vendor/d3.layout.min.js"></script>
<script src="../rickshaw.min.js"></script>

<div id="chart"></div>

<script>

var data = [ { x: 1910, y: 92228531 }, { x: 1920, y: 106021568 }, { x: 1930, y: 123202660 }, { x: 1940, y: 132165129 }, { x: 1950, y: 151325798 }, { x: 1960, y: 179323175 }, { x: 1970, y: 203211926 }, { x: 1980, y: 226545805 }, { x: 1990, y: 248709873 }, { x: 2000, y: 281421906 }, { x: 2010, y: 308745538 } ];

var graph = new Rickshaw.Graph( {
        element: document.querySelector("#chart"),
        width: 580,
        height: 250,
        series: [ {
                color: 'steelblue',
                data: data
        } ]
} );

graph.render();

</script>
