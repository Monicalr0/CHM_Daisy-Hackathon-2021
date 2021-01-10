# Game Report
## Game configuration
allocation_function: attractiveness_allocation

map_size: (400, 400)

population: 1000000.0

n_rounds: 10

starting_cash: 70000

profit_per_customer: 0.5

max_stores_per_round: 2

place_stores_time_s: 10

ignore_player_exceptions: True

store_config: {'small': {'capital_cost': 10000.0, 'operating_cost': 1000.0, 'attractiveness': 25.0, 'attractiveness_constant': 1.0}, 'medium': {'capital_cost': 50000.0, 'operating_cost': 2000.0, 'attractiveness': 50.0, 'attractiveness_constant': 1.0}, 'large': {'capital_cost': 100000.0, 'operating_cost': 3000.0, 'attractiveness': 100.0, 'attractiveness_constant': 1.0}}

## Players
- RandomPlayer-0
- CopyPlayer-1
## Final Scores
RandomPlayer-0: 353413.4405674626

CopyPlayer-1: 70000.0

# Winner!
RandomPlayer-0
