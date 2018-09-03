# dogo-cli
## Install
`npm install dogo-cli --global`

## Usage
1. 创建一个新项目：`dogo init <project-name>`
2. 使用SSH的方式创建新项目：`dogo init --ssh <project-name>`

## Option

* `dogo --help` 查看帮助信息
* `dogo --version` 查看版本信息
* `dogo init <project-name>` 默认情况下使用Http的方式拉取gitlab项目,需要SSH的使用 `dogo init -s <project-name>` 或 `dogo init --ssh <project-name>`
