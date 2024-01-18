---
toc: True
comments: True
layout: post
title: Admin Panel Ideation
description: Admin Panel Ideation - Week 19 work
type: tangibles
courses: { 'csa': {'week': 19} }
---

# Admin Panel Purpose

The Admin Panel is meant to allow admins in order to view sensitive data. This sensitive data may include project ideas, payment details, places of employment, etc., thus it must be extremely protected and under lock and key in order for it to be accessed.

# Reqs. Admin Panel Fills

## Spring Requests

This code will also host an API that can be requested, allowing the frontend to request the basic data. However more advanced data can be requested

## Thymeleaf

The admin panel will allow for ease of CRUD requests, especially PUT and DELETE requests, which are items that might be managed by an admin. This is also used for displaying data, including visits, fundraising, supporters, etc. for ease of use or whatever need be. It could also be used in order to create and fill certain requirements

## JWT

This will use JWT tokens and cookies to manage requests to the Admin panel and its API, and to log into the actual panel. There are also PAT/OTPs in order to become an admin.

# Admin Panel Plan and Ideation

1. Basic Login

Allow admins to log in, prompt for a Username and Password. This allows them to look at separate messages, projects, and the support they've gotten. They also can see trending items.

2. Editing Items

This admin panel can allow them to edit or delete bad plans that overall are not useful or effective as products. Also allows admins to remove inappropriate ideas/plans

3. Signing Up

We can allow people to sign up for an Admin or API key, and by doing that allow people to access our ideas as an API. However, when signing up, they will need to be assigned for a role, and I'd like to add an OTP (one time password) to allow for a process where we allow people to access potentially access sensitive data

