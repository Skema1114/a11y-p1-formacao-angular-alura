# A11yP1FormacaoAngularAlura

This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 12.0.1.

## Development server

Run `ng serve` for a dev server. Navigate to `http://localhost:4200/`. The app will automatically reload if you change any of the source files.

## Code scaffolding

Run `ng generate component component-name` to generate a new component. You can also use `ng generate directive|pipe|service|class|guard|interface|enum|module`.

## Build

Run `ng build` to build the project. The build artifacts will be stored in the `dist/` directory.

## Running unit tests

Run `ng test` to execute the unit tests via [Karma](https://karma-runner.github.io).

## Running end-to-end tests

Run `ng e2e` to execute the end-to-end tests via a platform of your choice. To use this command, you need to first add a package that implements end-to-end testing capabilities.

## Further help

To get more help on the Angular CLI use `ng help` or go check out the [Angular CLI Overview and Command Reference](https://angular.io/cli) page.

# Comandos utilizados

ng g m shared/components/yes-no-button-group

ng g c shared/components/yes-no-button-group

# Anotações

- A sintaxe `[(value)]="yesNoAnswer"` só funciona trocando os valores da tela na doom porque o input chama-se `value` e o output com o event chama-se `valueChange`, este que possui o `EventEmitter`. Senão teria que ser `[value]="yesNoAnswer" (valueChange)="yesNoAnswer = $event"`;
- Com o `ngSubmit` caso ocorra algum erro, não haverá refresh na mesma, diferente se usar o `submit`;
- o `forwardRef()` é utilizado quando o `acessor token` é declarado mas ainda não foi definido, seria a referencia de algo que ainda esta para existir;
-
