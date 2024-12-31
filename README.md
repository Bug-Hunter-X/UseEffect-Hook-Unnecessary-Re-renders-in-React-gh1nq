# React useEffect Hook Unnecessary Re-renders
This repository demonstrates a common issue with the React `useEffect` hook where it re-renders more often than necessary.  The problem lies in the dependency array.  The provided solution demonstrates a correct usage of the dependency array and explains how to improve performance. 

## Problem
The `useEffect` hook is intended to perform side effects. However, if the dependency array is incorrect, it will run more often than desired leading to performance issues and potential bugs.

## Solution
The correct implementation ensures that the effect only runs when the count changes, preventing unnecessary re-renders.