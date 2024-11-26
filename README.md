# React Router v7 - useNavigate Bug

This repository reproduces a `Error: useNavigate() may be used only in the context of a <Router> component.` error.
Since this repository relies on a public _and_ secret key for [Clerk](https://clerk.com) I won't publicly share my credentials here. Either create an account on Clerk or ask me to share them for testing purposes.

Steps to reproduce:

1. Install deps with `pnpm install`
1. Copy `.env.example` to `.env` and fill out the publishable key and secret key (from your Clerk dashboard)
1. Start the development server with `pnpm run dev`