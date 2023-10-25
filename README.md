# Validation-REST-API-example

Spring Boot CRUD REST APIs Validation Example

**Steps to use Validation**

•Hibernate Validator available on the classpath when we use Spring Boot Starter Web.

•Apply validation annotations to a bean. For example, @NotNull, @Email, @NotBlank, and @Size validations.

•Enable validation on Spring Rest Controller by adding @Valid annotation in addition to @RequestBody.

•To customize response validation we need to extend ResponseEntityExceptionHandler class and override 
 handleMethodArgumentNotValid(MethodArgumentNotValidException ex, HttpHeaders headers, HttpStatus status, WebRequest request) 
 method.

**Tools and Technologies Used**

  Spring Boot 3+ , JDK 17 or later, MySQL, **IDE** - STS.

  **JSON object**

  {
  "firstName": "John",
  "lastName": "Doe",
  "emailId": "john.doe@example.com"
}
