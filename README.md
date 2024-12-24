# React Native FlatList Key Error

This repository demonstrates a common error in React Native's FlatList component: using duplicate or inconsistent keys for list items. This can lead to incorrect rendering or flickering.

## Problem

The `keyExtractor` function in FlatList must provide a unique key for each item. Failure to do so can cause the FlatList to malfunction.

## Solution

Ensure that the `keyExtractor` function generates unique keys for every item in your data array.  UUIDs or a combination of unique identifiers is a best practice.

## Setup

1. Clone the repo
2. Run `npm install`
3. Run `npx react-native run-android` or `npx react-native run-ios`

