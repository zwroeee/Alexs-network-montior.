
```markdown
# Network Monitor

Welcome to my **Network Monitor** application! This is a Python-based network monitoring tool that I developed to help users track their network activity in a user-friendly way. It provides real-time statistics, visualizations, and insights into which processes consume the most bandwidth.

## Features

- **Monitor Network Traffic**: Easily track the number of bytes sent and received over time.
- **Graphical Visualization**: View network activity in real-time graphs to understand your network usage better.
- **Top Talkers**: Identify which! processes are the biggest consumers of bandwidth.
- **Customizable Monitoring Interval**: Adjust the frequency of monitoring through an easy-to-use configuration panel.
- **Theme Toggle**: Switch between light and dark modes to suit your preferences.
- **Log Export**: Automatically saves network activity to a CSV file for your records.

## Installation

### Prerequisites

Make sure you have Python 3.x installed. You can get it from [python.org](https://www.python.org/downloads/).

### Clone the Repository

To get started, clone the repository to your local machine:

```bash
git clone https://github.com/zwroeee/network-monitor.git
cd network-monitor
```

### Create a Virtual Environment (Optional but Recommended)

I recommend using a virtual environment to manage dependencies for the project:

```bash
python -m venv venv
source venv/bin/activate # On Windows use `venv\Scripts\activate`
```

### Install Requirements

Next, install the required packages by running:

```bash
pip install -r requirements.txt
```

### Building the Executable

If you haven’t done so yet, you’ll need to build the executable for the application. You can do this using a packaging tool like `PyInstaller`. Run the following command to create the executable:

```bash
pyinstaller --onefile main.py  # Replace `main.py` with your main file if necessary
```

Once the build process is complete, the executable will be located in the `dist` folder.

### Running the Application

To run the application, navigate to the `dist` folder and open the executable file:

```bash
cd dist
./network_monitor.exe  # On Windows
# OR
./network_monitor  # On macOS/Linux, if you built it for those systems
```

## Usage

1. Launch the application by double-clicking the executable.
2. Click on **Start Monitoring** to start tracking your network activity.
3. Watch the log area for real-time updates on your network usage.
4. Click **Show Graph** to visualize how your network usage changes over time.
5. Use **Show Top Talkers** to see which processes are using the most bandwidth.
6. Feel free to adjust the monitoring interval in the **Configuration** panel to suit your needs.
![Capture5](https://github.com/user-attachments/assets/49575ea0-702a-48cd-a713-b1875ee273f5)
![Captur2](https://github.com/user-attachments/assets/21d850c8-178e-4197-9129-3595290e92dd)
## Contributing

If you have ideas for enhancements or new features, don’t hesitate to open an issue or submit a pull request.

1. Fork the repository.
2. Create your feature branch (`git checkout -b feature/YourFeature`).
3. Commit your changes (`git commit -m 'Add some feature'`).
4. Push to the branch (`git push origin feature/YourFeature`).
5. Open a pull request.

## License

This project is licensed under the MIT License. You can find more details in the [LICENSE](LICENSE) file.

## Acknowledgements

- A big thank you to [psutil](https://github.com/giampaolo/psutil) for providing an easy way to retrieve information on running processes and system utilization.
- Special appreciation to [Matplotlib](https://matplotlib.org) for enabling the graphical representations of network usage.

---

Feel free to reach out if you have any questions, suggestions, or if you just want to say hi. Enjoy using the Network Monitor!
```
