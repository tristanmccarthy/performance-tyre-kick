Allows a quick performance test of a url.

Specify thread count, test duration (seconds) and the url to target:

mvn clean install -DperfTest.hostName=http://www.google.co.uk -DperfTest.threadCount=1 -DperfTest.durationSeconds=10

Results are logged to ../target/jmeter/results