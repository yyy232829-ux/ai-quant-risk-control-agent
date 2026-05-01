# AI Quant Risk Control Agent

This project is an AI-assisted workflow for quantitative trading system refactoring, risk-control review, and safety validation.

## Purpose

The goal is to use large language models as coding and reasoning agents to help analyze, refactor, and validate a Python-based quant trading system.

The agent is designed to assist with:

- Backtesting logic review
- Live trading safety boundary checks
- Kill switch validation
- Position limit control
- Small-position testing
- Limit expansion after stability verification
- Automatic downgrade mechanism
- Log analysis
- Test command generation
- Multi-model cross-checking

## Current Development Stage

The project is currently in local development and safety testing.

The live trading mode is intentionally restricted during the review phase:

- No real order placement
- No order cancellation
- No forced position closing
- No removal of kill switch
- No second live execution without review
- No treating review status as permission to increase position size

## Planned Agent Workflow

The AI agent will help with:

1. Reading and analyzing Python trading code
2. Detecting unsafe trading logic
3. Generating test cases
4. Reviewing logs and backtest output
5. Producing risk downgrade plans
6. Comparing outputs from different LLMs
7. Creating staged rollout plans for small-position testing

## MiMo Evaluation Plan

I plan to evaluate MiMo models on:

- Long-context code understanding
- Chinese technical instruction following
- Quant trading risk reasoning
- Safety boundary detection
- Automated test generation
- Refactoring suggestions
- Agent workflow planning

## Disclaimer

This project is for research, development, and safety validation only.  
It does not provide financial advice and does not execute real trades during the review phase.
