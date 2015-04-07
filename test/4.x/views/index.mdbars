# {{title}}
Welcome to {{title}}

## Basic Test

Hello, my name is {{name}}. I am from {{hometown}}.
I have {{kids.length}} kids:

{{#kids}}
 * {{name}} is {{age}}
{{/kids}}

## Path Test

```
person.name = {{person.name}}
```
```
../company.name = {{#person}}{{name}} - {{../company.name}}{{/person}}
```

## Escape Test

 * Unescaped: {{escapee}}
 * Escaped: {{{escapee}}}

## Handlebars Helper Test

{{#posts}}
 * {{{link_to this}}}
{{/posts}}


## Handlebars Helper with String Test

{{#posts2}}
 * {{{link_to2 "Post" this}}}
{{/posts2}}

## Handlebars Block Helper Test
{{#list people}}
{{firstName}} {{lastName}}
{{/list}}

## Handlebars 'with' Block Helper Test

{{#list people2}}{{#with name}}{{firstName}} {{lastName}}{{/with}}{{/list}}

## Handlebars Partial Test

{{#people3}}
 * {{> link2}}
{{/people3}}