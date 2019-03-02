**Please note! These features will only work for version 3.0.0 and above! Ensure that you are using the right version of YamlToBot for this to work!**

As of YamlToBot 3.0.0, you are able to define your own text variables and use them in your commands.

## Table of Options

| Value Name  | Type  | Description | Default |
|-------------|---------|--------------------------------------------------------------------------------------------------|---------------|
| key | String | The name of the variable | null |
| value | String | The value of the variable that is put wherever the variable is called | null |

## Defining a variable

Definining a variable is incredibly simple. All it requires is the creation of a `variables` sequence in your config and adding your variables to it.

```yaml
variables:
  -
    key: "ytb"
    value: "YamlToBot"
```

## Calling a variable

To use your variable in your command messages, simply use a percent sign, your variable key, and another percent sign.

```yaml
  -
    name: "variable"
    description: "Tests using a variable in YamlToBot."
    message:
      - "This bot was made with %ytb%!"
```
