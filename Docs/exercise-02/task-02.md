---
title: '02. Configure Copilot'
layout: default
nav_order: 2
parent: 'Exercise 02: Configure Knowledge Management functionality and tailor the environment'
---

# Task 02: Configure Copilot

## Introduction

The Knowledge Management agent uses the Copilot settings of your tenant to ensure that it creates knowledge articles as needed. To ensure that it can do this effectively, you're going to configure it to ensure that it is using your organization's internal Dynamics 365 knowledge management functionality.

## Description

In this task, you'll configure Copilot for Questions and email to include a knowledge source and explicitly use your organization's Dynamics 365 knowledge base as the knowledge source required for the Knowledge Management Agent to function.

## Success criteria

- Copilot is configured to use the organization's Dynamics 365 knowledge base as its active knowledge source.

## Steps

1. Open **Copilot Service admin Center**.

    ![Copilot Service admin Center](../../media/rtfwkd19.jpg)

1. In the left pane, in the **Support experience** section, select **Productivity**.

    ![Productivity in Support experience](../../media/l3q53h1b.jpg)

1. Locate **Copilot for Questions and email** and then select **Manage**.

    ![Manage Copilot for Questions and email](../../media/vfbqctod.jpg)

1. Move down to the **Knowledge sources** section and select **Include a knowledge base or another type of knowledge source**. Then, select **Use your organization's knowledge base as knowledge source**.

    {: .warning }
    > The knowledge management agent will only work if you're using the built-in Dynamics 365 knowledge base.

    ![Knowledge sources settings](../../media/image008.png)

1. On the command bar, select **Save and Close**.
