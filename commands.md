# Run agent with a problem

docker compose run --remove-orphans test --agent-file /workspace/myagent/agent.py --problem-file /workspace/myagent/problems/problem_suite_v3/problem-000.jsonl --max-workers 1 --skip-reasoning true --timeout 300