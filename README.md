# Hangman Spring Boot Application

## Technical Architecture Log

- **Core Contracts**: Defined WordRepository and HangmanRenderer interfaces.
- **Data Layer**: Implemented ClasspathWordRepository with java.util.Random for random word selection.
- **Render Layer**: Implemented AsciiArtRenderer to parse frames from assets.
- **Bootstrap**: Integrated @SpringBootApplication and @ComponentScan parameters.
