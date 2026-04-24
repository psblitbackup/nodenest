cat > tutorials/day-02-modules-controllers-services.md <<'EOF'
# Day 2: NestJS Modules, Controllers, and Services

## Goal

In Day 2, you will learn the three most important building blocks of a NestJS application:

- Module
- Controller
- Service

## 1. What is a Module?

A module is a class that organizes related features together.

In NestJS, every application has at least one root module called `AppModule`.

Example:

```ts
import { Module } from '@nestjs/common';

@Module({})
export class AppModule {}