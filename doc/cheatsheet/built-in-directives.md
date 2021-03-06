@cheatsheetSection
Built-in directives
@cheatsheetIndex 2
@description
Available using `platform_directives` in pubspec

@cheatsheetItem
syntax:
`<section *ngIf="showSection">`|`*ngIf`
description:
Removes or recreates a portion of the DOM tree based on the `showSection` expression.

See: [Template Syntax](/angular/guide/template-syntax),
[NgIf class](/angular/api/angular2.common/NgIf-class)


@cheatsheetItem
syntax:
`<li *ngFor="let item of list">`|`*ngFor`
description:
Turns the li element and its contents into a template, and uses that to instantiate a view for each item in list.

See: [Template Syntax](/angular/guide/template-syntax),
[NgFor class](/angular/api/angular2.common/NgFor-class)


@cheatsheetItem
syntax:
`<div [ngSwitch]="conditionExpression">
  <template [ngSwitchWhen]="case1Exp">...</template>
  <template ngSwitchWhen="case2LiteralString">...</template>
  <template ngSwitchDefault>...</template>
</div>`|`[ngSwitch]`|`[ngSwitchWhen]`|`ngSwitchWhen`|`ngSwitchDefault`
description:
Conditionally swaps the contents of the div by selecting one of the embedded templates based on the current value of conditionExpression.

See: [Template Syntax](/angular/guide/template-syntax),
[NgSwitch class](/angular/api/angular2.common/NgSwitch-class),
[NgSwitchWhen class](/angular/api/angular2.common/NgSwitchWhen-class),
[NgSwitchDefault class](/angular/api/angular2.common/NgSwitchDefault-class)

@cheatsheetItem
syntax:
`<div [ngClass]="{active: isActive, disabled: isDisabled}">`|`[ngClass]`
description:
Binds the presence of CSS classes on the element to the truthiness of the associated map values. The right-hand expression should return {class-name: true/false} map.

See: [Template Syntax](/angular/guide/template-syntax),
[NgClass class](/angular/api/angular2.common/NgClass-class)

<!-- Why isn't NgStyle in here or in the TS cheat sheet? -->
