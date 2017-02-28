# jmeter-ant

A Simple Ant project for JMeter Performance Test

# Pre-Requisite
* Java 1.7 or above
* JMeter 3.1 or above
* JMETER_HOME variable is set


#Usage

* To clean the current project by removing the temp folders and files

```
ant clean
```

* To show the current test input parameters

```
ant show-test-properties
```

* To run the JMeter Performance Test

```
ant run
```

* To generate HTML report

```
ant generate-report
```

* To generate charts

```
ant generate-chart
```

To generate we need to have required plugins. If they are not present,

```
ant install-plugins
```

will take care of installing necessary plugins


======================

To run all the tasks in a proper order

```
ant all
```
