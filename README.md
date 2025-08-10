# What I in envision

I would love a graph that would show how the payments could change as I increase them. 

want to do a build up curve for the various things

Would love to have a gradient Stacked Area Chart as such
https://echarts.apache.org/examples/en/editor.html?c=area-stack-gradient

reload the data on graph slider with change javascript
`
    const ctx = document.getElementById('myChart').getContext('2d');
    const chart = new Chart(ctx, {
    // ... Chart configuration
    });

    slider.addEventListener('change', () => {
    const newData = fetchData(slider.value); 
    chart.data.datasets[0].data = newData;
    chart.update();
    });
`

https://codepen.io/EbrahimKaram/pen/wBwxbLL


# Resources

Chat GPT 5
