
REGION=us-east-1

attach:
	aws --profile ${CLUSTER_NAME} \
		iam --region ${REGION} 
		attach-role-policy \
		--role-name sc-staging-startree-dev-ui-team20220113030258471200000009 \
		--policy-arn arn:aws:iam::462173948356:policy/devrel-demos-policy
