# Flowtree

There are many mature network technologies in the market such as zigbee, z-wave, echonet, which can collect home or building meter data into central database. assume we collect data every 15 minutes and store into some data storage, e.g. csv file, hdfs, database, the data format looks like

Time Milliseconds, Meter id, city, region, power usage

1234567890, 123, 456, 678, 1234567890

Let’s find the following:

1> How big data will be in a year, 5 years, 10 years, etc…, find an algorithm to simulate the data or search online to find public data.

2> How we store data into some data storage, e.g. csv file, hdfs, database, etc…

3> How to aggregate data by location: city, region and by time: hour, day, month, year

4> There is usually power usage peak in summer, let’s predicate when it will be next year.

We have 3 teams by course: DS-200(Hadoop), DS-300(Spark), DS-400(AI). Each team should focus on using its own technology to solve the problem by choosing right storage, right tools, right presentation, etc…

You may reference Google TensorFlow, But our clients prefer us since they don’t like Google. (It’s not a joke!)

You may also reference market solutions from GE or AutoGrid . They provide cloud solutions. Assume they are your strong competitors. (Work out a plan to beat them!)

If you feel really good about yourself after finishing project, we encourage you join a TopCoder competition. here is the link: http://predix.topcoder.com/
