create_project:
	vivado -mode batch -source tcl/create_project.tcl -nojournal -nolog

clean:
	rm -rf .Xil simulation.cache simulation.hw simulation.ip_user_files simulation.sim simulation.xpr simulation.runs vivado*

gui:
	vivado simulation.xpr -nolog -nojournal
