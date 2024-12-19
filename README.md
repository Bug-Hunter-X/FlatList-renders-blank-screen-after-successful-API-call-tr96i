# React Native FlatList Blank Screen Bug

This repository demonstrates a common bug in React Native where a FlatList component renders a blank screen even after successfully fetching data from an API. The issue is resolved by carefully managing the loading and error states of the component.

## Bug Description
The `DataFetch` component fetches data from a public API. While the data is fetched correctly, the `FlatList` does not render the data and only shows a blank screen. 

## Solution
The solution involves proper handling of the loading and error states, including showing an ActivityIndicator while loading and providing an error message if an error occurs during the fetch process.