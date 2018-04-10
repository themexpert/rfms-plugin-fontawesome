# FontAwesome Plugin for React FileManager
> This is server side plugin. Dependent on React FileManager server side library.

#### Dependencies

FileManager: https://github.com/themexpert/react-filemanager-server 

Front-end plugin: https://github.com/themexpert/rfm-plugin-fontawesome

#### Installation

`composer require themexpert/rfms-plugin-fontawesome`

#### Usage

```PHP
    $config = [
            //...
            "plugin" => [
                        \FontAwesome\FontAwesome::class
                    ]
        ];
    (new FileManager($config));
```
