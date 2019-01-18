<template>
    							<section id="four" >
								<div class="container">
									<p id="show"> </p>
									<h2 id="hide">Contact Me</h2>
									<p id="hid">Feel free to send me a message if you have any question or have any concerns. I will get back at you as soon as a possible. Thank you.</p>
									<form method="POST" id="form">
										<div class="row uniform">
											<div class="6u 12u(xsmall)"><input type="text" name="name" id="name" placeholder="Name" required/></div>
											<div class="6u 12u(xsmall)"><input type="email" name="email" id="email" placeholder="email@email.com" required/></div>
										</div>
										<div class="row uniform">
											<div class="12u"><input type="text" name="subject" id="subject" placeholder="Subject" required/></div>
										</div>
										<div class="row uniform">
												<div class="12u">
													<div class="select-wrapper">
														<select name="category" id="category" required>
															<option value="">- Category -</option>
															<option value="1">Comments</option>
															<option value="2">Question</option>
															<option value="3">Jop Opportunities</option>
															<option value="4">Other</option>
														</select>
													</div>
												</div>
											</div>
										<div class="row uniform">
											<div class="12u"><textarea type="text" name="message" id="message" placeholder="Message..." rows="6" required></textarea></div>
										</div>
										<div class="row uniform">
											<div class="12u">
												<ul class="actions">
													<li><input id="submit" name="submit" type="submit" class="special" value="Send Message" onsubmit="return isComplete"/></li>
													<li><input type="reset" value="Reset Form" /></li>
												</ul>
											</div>
										</div>
									</form>
								</div>
							</section>
</template>
<script>
export default {
  name: "SectionFour"
};
</script>
