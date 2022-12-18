# Rustの開発環境

Microsoftが提供しているテンプレートがあるので、それを元に開発環境を整えます。

[Rustのdevcontainer](https://github.com/devcontainers/images/tree/main/src/rust)

このイメージ「mcr.microsoft.com/devcontainers/rust」ではRustのバージョンを指定することはできません。Rustにはeditionという画期的な仕組みがあり、後方互換性のない変更はeditionを変更しない限り有効になりませんが、プロジェクトの方針でRustのバージョンを固定しなければならない場合は[Rustのdevcontainer](https://github.com/devcontainers/images/tree/main/src/rust)の.devcontainer/Dockerfileで指定する[DOCKER OFFICIAL IMAGE](https://hub.docker.com/_/rust)のrustのバージョンを変更する必要があります。
