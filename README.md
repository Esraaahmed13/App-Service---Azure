# App-Service-Azure
@{
    var myChart = new Chart(width: 600, height: 400)
        .AddTitle("Chart Title")
        .AddSeries(
            name: "Employee",
            xValue: new[] {  "Peter", "Andrew", "Julie", "Mary", "Dave" },
            yValues: new[] { "2", "6", "4", "5", "3" })
        .Write();
}
