FROM mcr.microsoft.com/devcontainers/typescript-node:0-18-bullseye

RUN apt -y update
RUN npm install -g playwright@latest
RUN npx playwright install-deps

ENV PLAYWRIGHT_BROWSERS_PATH=/usr/local/ms-playwright
RUN npx playwright install chromium ffmpeg
