
# JADE Book Trading Project

Book Trading is a example agent project for learning JADE Agent Development library.
## Technologies

- Java 1.8
- JADE 4.5.0
- Maven



## How to Run

Clone the project

```bash
git clone https://github.com/omerfarukalaca/jade-book-trading.git
```

Go to the project directory

```bash
cd jade-book-trading
```

Deploy jade.jar for local maven repository.

```bash
mvn deploy:deploy-file -Durl=file://repo -Dfile=repo/jade-4.5.0.jar -DgroupId=com.tilab.jade -DartifactId=jade -Dpackaging=jar -Dversion=4.5.0
```

Build the project

```bash
mvn clean package
```

Run the project.

```bash
java -jar target/jade-book-trading-1.0-SNAPSHOT-jar-with-dependencies.jar -gui
```

  
