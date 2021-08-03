# Florence Spark Exercises

## Spark Installation

1. Install Java

    ```
    brew tap adoptopenjdk/openjdk
    brew install adoptopenjdk11
    ```

2. Install `pyspark`

    ```
    python -m pip install pyspark
    ```

3. Test it out to make sure it works

    ```
    >>> import pyspark
    >>> spark = pyspark.sql.SparkSession.builder.getOrCreate()
    >>> spark.range(6).show()
    +---+
    | id|
    +---+
    |  0|
    |  1|
    |  2|
    |  3|
    |  4|
    |  5|
    +---+
    ```


